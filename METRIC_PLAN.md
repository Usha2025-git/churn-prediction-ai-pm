# Metrics & Analytics Plan - Churn Prediction

## Business Metrics - North Star
- **Churn Rate**: 35% → 26% target
- **CLV Growth**: $2,500 → $2,900 (+16%)
- **Campaign ROI**: >3x return per dollar

## Model Metrics
- **AUC-ROC**: 0.85+ (vs 0.62 baseline)
- **Precision@10%**: >0.65
- **Recall**: >0.40 (catch churners)
- **Fairness**: Demographic parity <5%

## Evaluation
- 5-fold CV on 2 years historical
- 8-week A/B test: 50K users per arm
- Success: 20% churn reduction, positive ROI
- Quarterly fairness audits
