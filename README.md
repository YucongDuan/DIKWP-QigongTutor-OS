# DIKWP QigongTutor OS

Created by Yucong Duan (段玉聪).

DIKWP QigongTutor OS is a GitHub-ready learning and teaching system for qigong education under DIKWP-Mesh 4.0 SemanticClosure.

It helps students, teachers and community instructors organize qigong learning as a safe, evidence-aware, non-medical wellness education workflow.

## Core boundary

This system is for wellness education, gentle movement learning, teacher lesson planning and reflection. It is not medical diagnosis, treatment, rehabilitation prescription, emergency care or disease cure.

## Quick start

```bash
pip install -e .
qigong-tutor analyze examples/sample_qigong_learning_case.json --out outputs/demo
qigong-tutor guard "learn Baduanjin for relaxation"
qigong-tutor static-audit src --out outputs/demo/static_boundary_audit_report.json
```

Open `index.html` for a standalone browser demo.

## Outputs

- `qigongtutor_report.json`
- `dikwp_practice_ledger.json`
- `student_study_plan.md`
- `teacher_lesson_pack.md`
- `safety_boundary_report.md`
- `misconception_map.csv`
- `action_tickets.csv`
- `recommendations.md`

## DIKWP mapping

Each learning module is registered as `C = (D, I, K, W, P, R)`:

- Data: form, module, learner context.
- Information: relation among breath, movement, attention, posture and safety.
- Knowledge: learning focus and qigong teaching structure.
- Wisdom: safety boundary and non-cure stance.
- Purpose: learner goals and feedback plan.
- Reliability: readiness, semantic stability, residual and review triggers.
