# Le vrai prix au m² (Appart Paris)

Web app (one `index.html`, French interface) to find the best-value apartment to buy in Paris from listings pasted from SeLoger.

- Paste a listing URL or its full text: fields are extracted automatically, then editable.
- Red flags: viager, occupied or rented, nue-propriété, auctions, offices, another city labelled Paris, impossible surfaces or prices per m², terrace counted in the surface, DPE F/G, ground floor, high floor without lift.
- Value score out of 100 (price/m² vs arrondissement average, DPE, floor, light, outdoor space, parking, charges, distance), with adjustable weights.
- Budget: notary fees, renovation for DPE F/G, total cost, monthly mortgage.
- Map by arrondissement, side-by-side comparison, visit checklist, notes and rating.
- Épargne & apport tab: savings accounts (Livret A, LDDS, LEP, current account) with balance, rate and cap; interest estimated by quinzaine; "Quand retirer ?" tool (which account first, which day loses no interest); apport goal from a target price or a saved listing, with progress and forecast; EUR → VND rate history (entered by hand), calculator and log of exchanges to compare services. Own JSON export/import. Personal tracking tool, not financial advice.
- Placement tab: dated research on where to put an apartment down payment (regulated savings, fonds euros, term deposits, money-market, target-maturity bond and MSCI World ETFs), risks, overlaps, decision table, allocation calculator and a checklist. Research snapshot of 26 Nov 2026, not financial advice.
- Data saved in the browser (localStorage), export/import JSON or CSV.

Open `index.html` in a browser, or enable GitHub Pages on this repo.

Default arrondissement averages: notaires' medians for older apartments, consulted March 2026 (via iad France). Editable in Réglages.

When opened as a Claude artifact, the app also syncs data across devices and offers "Extraire avec Claude"; those two features are not available on a plain website.
