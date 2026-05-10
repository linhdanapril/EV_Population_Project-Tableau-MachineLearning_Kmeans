🔋 Electric Vehicle Population Analysis

Washington State · 279,745 vehicles · Tableau + KMeans Clustering


📊 Tableau Dashboard
Interactive dashboard exploring the EV landscape across Washington State.

📈 EV growth trend (BEV vs PHEV) from 1999 to 2027
🗺️ Geographic density by county
🏆 Top 10 brands by registration volume
⚡ Average electric range by brand
✅ CAFV eligibility breakdown


🤖 KMeans Clustering (k = 4)
Segmented the full fleet into 4 meaningful groups using Vehicle Age, EV Type, Brand Range Encoding, and Model Popularity.
ClusterSegmentKey Brands0🟢 New premium BEVTesla1🔵 New mainstream BEVFord · Kia · Hyundai2🟡 Legacy BEVTesla (old) · Chevrolet · Nissan3🟠 PHEV hybridToyota · Jeep · BMW

Why clustering? 64% of BEV records have missing range data — unsupervised learning on the full dataset is more honest than supervised regression on a biased subset.


🗂️ Dataset
Electric Vehicle Population Data (Kaggle) — Washington State DOL
