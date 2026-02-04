## 🧩 What was deployed?

We released a new version of **Wilkins Operator IA** with two main updates:

1) **Photo capture is now handled by Wilkins Tracking (in-house)** instead of Scandit.  
2) Operators can now **add manual measurements** (L/W/H + weight) directly in the app, so they don’t always need to rely on the dimensioner (“the dim”) for every shipment.

This update also improves the capture flow messaging, so operators can clearly see when a photo is captured, uploading, or still syncing.

## 🎯 Customer impact

Customers will get **more complete shipment records**: photos are still captured reliably, and teams can now record measurements even when the dimensioner is unavailable, busy, or not required for a specific workflow.  
This reduces operational delays and improves continuity during peak hours or exception cases.

## 👀 Where will users notice it?

In **Wilkins Operator IA → Photo capture** step (now powered by Wilkins Tracking)  
In **Wilkins Operator IA → Measurements** step (new option to enter measurements manually)

## 🗣 How can I explain this to a customer?

“We updated Wilkins Operator IA so your team can capture shipment photos using our built-in Wilkins Tracking module.  
We also added the ability to enter measurements manually, which helps you keep shipments moving even if the dimensioning station isn’t used for a particular case.  
The result is fewer workflow interruptions and more complete shipment data.”

## 🏢 What other areas of the company does this affect?

Cross-team impact: **Support** and **Commercial / Customer Success**.

**Support:** new troubleshooting path for photo capture (Wilkins Tracking) and new guidance for manual measurement entry.
**Commercial / CS:** easier to position the update as “more flexibility + fewer operational blockers”, especially for warehouses with mixed workflows.

## 🔍 Justification

While Scandit performed well, it introduced ongoing licensing costs. Moving photo capture to **Wilkins Tracking** reduces costs and gives us more control over the long-term roadmap.  
Separately, customers requested a smoother fallback when dimensioning is not available or not necessary; enabling **manual measurements** ensures operations can continue without waiting on the dimensioner.

## 📽 Demo / Evidence

Loom demo (staging): https://www.loom.com/share/REPLACE_WITH_REAL_LINK  
Screenshots (before/after): https://REPLACE_WITH_REAL_LINK

## 🧯 Support notes / Risks

If a customer reports photo capture issues after the update, confirm they are on the latest Operator IA version and review the Wilkins Tracking capture states (captured → uploading → synced).
Manual measurements are intended as a fallback and for exception workflows; data entry should follow the agreed measurement standards (units/rounding).
Monitoring is enabled to track photo upload success rate and measurement completion rate after rollout.