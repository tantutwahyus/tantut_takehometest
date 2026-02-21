### <h2>Strategic Insights & Intent Signals (Price vs Year)</h2>

<h2>Strategic Insights Summary</h2>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Category</th>
    <th>Observation</th>
    <th>Interpretation</th>
    <th>Business Implication</th>
  </tr>

  <!-- Fuel Type -->
  <tr>
    <td><b>Fuel Type</b></td>
    <td>Diesel vehicles show higher price ceilings than Petrol.</td>
    <td>Diesel acts as a premium/resale-strength signal.</td>
    <td>Route Diesel-heavy newer cars to <b>Premium desk</b>.</td>
  </tr>

  <tr>
    <td><b>Fuel Type</b></td>
    <td>Hybrid prices trend higher in recent years.</td>
    <td>Strong demand for eco-efficient vehicles.</td>
    <td>Use Hybrid as primary signal for <b>Eco desk</b>.</td>
  </tr>

  <tr>
    <td><b>Fuel Type</b></td>
    <td>Petrol dominates lower-to-mid price bands.</td>
    <td>Mass-market positioning.</td>
    <td>Combine with Manual + Older year for <b>Budget desk</b>.</td>
  </tr>

  <!-- Transmission -->
  <tr>
    <td><b>Transmission</b></td>
    <td>Automatic vehicles consistently priced higher than Manual.</td>
    <td>Strong premium intent signal.</td>
    <td>Automatic → prioritize for <b>Premium routing</b>.</td>
  </tr>

  <tr>
    <td><b>Transmission</b></td>
    <td>Manual vehicles cluster in lower price bands.</td>
    <td>Budget positioning.</td>
    <td>Manual + Older year → <b>Budget desk</b>.</td>
  </tr>

  <!-- Model -->
  <tr>
    <td><b>Model</b></td>
    <td>RAV4 shows highest price band across years.</td>
    <td>Premium SUV positioning.</td>
    <td>Strong <b>Premium segment</b> indicator.</td>
  </tr>

  <tr>
    <td><b>Model</b></td>
    <td>C-HR &amp; Auris sit in mid-to-upper band.</td>
    <td>Higher trim/crossover positioning.</td>
    <td>Consider Premium or upper-mid segment.</td>
  </tr>

  <tr>
    <td><b>Model</b></td>
    <td>Yaris &amp; Aygo dominate lower price band.</td>
    <td>Entry-level segment.</td>
    <td>Primary candidates for <b>Budget desk</b>.</td>
  </tr>

  <!-- Year -->
  <tr>
    <td><b>Year</b></td>
    <td>Newer year consistently correlates with higher price.</td>
    <td>Strongest universal driver.</td>
    <td>Use Year as base filtering logic before segmentation.</td>
  </tr>
</table>

<br/>

<h2>Feature Strength Ranking (Visual Hypothesis)</h2>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Rank</th>
    <th>Feature</th>
    <th>Reason</th>
  </tr>
  <tr>
    <td>1</td>
    <td><b>Year</b></td>
    <td>Clear consistent upward trend across all segments.</td>
  </tr>
  <tr>
    <td>2</td>
    <td><b>Model</b></td>
    <td>Strong separation of price tiers.</td>
  </tr>
  <tr>
    <td>3</td>
    <td><b>Transmission</b></td>
    <td>Automatic vs Manual shows visible premium gap.</td>
  </tr>
  <tr>
    <td>4</td>
    <td><b>Fuel Type</b></td>
    <td>Diesel/Hybrid show premium behavior.</td>
  </tr>
  <tr>
    <td>5</td>
    <td><b>Mileage</b></td>
    <td>Negative correlation, strengthens prediction when combined with Year.</td>
  </tr>
</table>

<br/>

<h2>Strategic Routing Logic (High-Level)</h2>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Desk</th>
    <th>Primary Signals</th>
  </tr>
  <tr>
    <td><b>Premium</b></td>
    <td>Newer Year + Automatic/Semi-Auto + Diesel/Hybrid + SUV models (RAV4, C-HR)</td>
  </tr>
  <tr>
    <td><b>Budget</b></td>
    <td>Older Year + Manual + Petrol + Entry models (Aygo, Yaris)</td>
  </tr>
  <tr>
    <td><b>Eco</b></td>
    <td>Hybrid + High MPG + Smaller engine size</td>
  </tr>
</table>

<br/>

<h2>Intent Signal Analysis – Price vs Year</h2>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Observation (Visual Evidence)</th>
    <th>Interpretation</th>
    <th>Intent Signal Strength</th>
    <th>Business Implication</th>
  </tr>

  <tr>
    <td>Strong upward trend: newer vehicles consistently priced higher.</td>
    <td>Year is a dominant structural driver of resale value.</td>
    <td><b>Very Strong</b></td>
    <td>Use Year as primary baseline variable in pricing and routing logic.</td>
  </tr>

  <tr>
    <td>Steeper price increase after ~2014.</td>
    <td>Recent models experience accelerated valuation growth.</td>
    <td><b>Strong</b></td>
    <td>Vehicles 2015+ should be evaluated for Premium desk first.</td>
  </tr>

  <tr>
    <td>Older vehicles cluster tightly in lower price bands.</td>
    <td>Lower ceiling regardless of other features.</td>
    <td><b>Strong (for Budget)</b></td>
    <td>Pre-2012 vehicles are strong candidates for Budget routing.</td>
  </tr>

  <tr>
    <td>Newer vehicles show wider price dispersion.</td>
    <td>Other features (model, transmission, fuel type) amplify price within new-year group.</td>
    <td><b>Interaction Signal</b></td>
    <td>Combine Year + Model/Transmission for better segmentation accuracy.</td>
  </tr>

  <tr>
    <td>All models show consistent upward pattern across years.</td>
    <td>Year effect is universal across segments.</td>
    <td><b>Universal Intent Signal</b></td>
    <td>Year should be weighted heavily in predictive modeling.</td>
  </tr>
</table>

<br/>

<h2>Strategic Interpretation – Year as an Intent Signal</h2>

<table border="1" cellpadding="8" cellspacing="0">
  <tr>
    <th>Intent Type</th>
    <th>Signal Pattern</th>
    <th>Operational Use</th>
  </tr>

  <tr>
    <td><b>High Resale Value Intent</b></td>
    <td>Newer Year (especially 2015+)</td>
    <td>Prioritize for Premium desk and higher marketing visibility.</td>
  </tr>

  <tr>
    <td><b>Fast Sale Intent</b></td>
    <td>Mid-age vehicles (2014–2017) priced competitively</td>
    <td>These may move faster due to affordability + acceptable recency.</td>
  </tr>

  <tr>
    <td><b>Budget Market Intent</b></td>
    <td>Older Year + Lower price clustering</td>
    <td>Route directly to Budget desk to reduce handling time.</td>
  </tr>
</table>

<br/>

<h3>Analytical Conclusion</h3>
<p>
Based on visual evidence, <b>Year is the strongest standalone intent signal</b> in the dataset.
It consistently explains structural price shifts across fuel types, transmission types, and models.
Other features refine price positioning, but Year establishes the baseline valuation band.
</p>