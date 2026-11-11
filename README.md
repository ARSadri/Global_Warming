# Pre-Feasibility Framework for Low-Head Coastal Microalgal Cultivation, In-Pond Decanting, and Sand-Capped Burial in Mine Voids

**The Solar-Pumped Marine Algae Mine Vault (SPAM-V): A Falsifiable Carbon-Fate and Engineered-Turbidite Architecture**

---

## Abstract

The Solar-Pumped Marine Algae Mine Vault (SPAM-V) is a falsifiable engineering and biogeochemical framework designed to evaluate whether low-head coastal microalgal cultivation coupled with agricultural-waste valorization and sand-capped mine-void burial can achieve durable, net-negative atmospheric Carbon Dioxide Removal (CDR). Previous marine biomass burial concepts have been constrained by prohibitive dewatering energy penalties, massive hydraulic transfer volumes, synthetic fertilizer emissions, or unverified open-ocean carbon fate. This revised SPAM-V architecture resolves those bottlenecks through a six-part physical sequence: (1) pumping seawater at ultra-low static head ($1\text{--}2\text{ m}$) into shallow, plastic-lined (geomembrane) coastal pools adjacent to a deep coastal mine pit; (2) fertilizing the seawater with treated agricultural waste to drive dense microalgal blooms; (3) dosing flocculants directly within the shallow pools to settle the algae in situ; (4) decanting $95\text{--}98\%$ of the clarified supernatant water back to the sea against minimal head ($\approx 1\text{ m}$); (5) gravity-flushing or low-head pumping the remaining concentrated bottom algal sludge into the center of the adjacent deep mine pit; and (6) periodically spreading thin layers of sand over the accumulated benthic mud to drive Terzaghi surcharge consolidation and form laminated, anoxic "engineered turbidites." We contextualize the single-pit and $1,000$-pit global scaling potential against existing CDR pathways and formalize the complete Pool $\times$ Destination state-flux matrix, dimensionally consistent climate-forcing ledger ($\mathrm{tCO_2e}$), agricultural-carbon attribution rules, and an eight-gate Bayesian falsification sequence.

---

## 1. Introduction and Global Carbon Dioxide Removal Context

### 1.1 The Carbon Dioxide Removal Imperative and Limitations of Current Pathways

Stabilizing global mean surface temperatures within international climate targets requires not only rapid decarbonization of industrial emissions, but also the deployment of $5\text{ to }10\text{ GtCO}_2\text{ yr}^{-1}$ of durable Carbon Dioxide Removal (CDR) by mid-century. However, currently deployed CDR methodologies face severe trade-offs among areal efficiency, energy intensity, cost, land-use competition, and monitoring, reporting, and verification (MRV) tractability:

* **Direct Air Capture with Geological Storage (DACCS):** Engineered chemical contactors capture $\mathrm{CO_2}$ directly from ambient air ($\approx 425\text{ ppm}$) and inject it into deep geological formations. While storage permanence exceeds $1,000\text{ years}$, capturing $\mathrm{CO_2}$ from dilute air is thermodynamically costly, requiring $1.5\text{ to }2.5\text{ MWh}$ of energy per tonne of $\mathrm{CO_2}$ and capital-intensive infrastructure. Current operational plants capture between $4,000\text{ and }36,000\text{ tCO}_2\text{ yr}^{-1}$, with next-generation commercial hubs targeting $0.5\text{ MtCO}_2\text{ yr}^{-1}$ at costs frequently exceeding USD $500\text{ to }1,000\text{ tCO}_2^{-1}$.
* **Bioenergy with Carbon Capture and Storage (BECCS):** Industrial biomass combustion or fermentation paired with point-source carbon capture can remove $0.5\text{ to }2.0\text{ MtCO}_2\text{ yr}^{-1}$ per large facility, but large-scale deployment competes directly with global food production, freshwater supplies, and terrestrial biodiversity for arable land.
* **Afforestation and Reforestation:** Terrestrial forestry is low-cost (USD $20\text{ to }100\text{ tCO}_2^{-1}$) but exhibits low areal productivity—typically capturing $3\text{ to }15\text{ tCO}_2\text{ ha}^{-1}\text{ yr}^{-1}$ ($300\text{ to }1,500\text{ tCO}_2\text{ km}^{-2}\text{ yr}^{-1}$)—and suffers from high reversal risk due to wildfires, drought, pest outbreaks, and timber harvesting over multi-decade timescales.
* **Open-Ocean Biomass Sinking and Ocean Alkalinity Enhancement (OAE):** Sinking macroalgae or microalgae in the open ocean avoids terrestrial land constraints, but once biomass sinks into the unenclosed abyssal ocean, directly measuring sediment remineralization, benthic methane generation, and deep-water carbon return over $100\text{ years}$ is practically impossible, creating severe regulatory and MRV barriers.

| CDR Pathway | Areal Yield ($\mathrm{tCO_2\ km^{-2}\ yr^{-1}}$) | Facility Scale ($\mathrm{tCO_2\ yr^{-1}}$) | Primary Bottleneck | MRV Profile |
| :--- | :--- | :--- | :--- | :--- |
| **Afforestation** | $300\text{--}1,500$ | $10,000\text{--}500,000$ | Land and water footprint | Reversal risk ($10\text{--}50\text{ yr}$) |
| **Enhanced Weathering** | $100\text{--}500$ | $10,000\text{--}200,000$ | Grinding energy and kinetics | Open-system soil/river MRV |
| **Direct Air Capture** | High (compact) | $4,000\text{--}500,000$ | Energy ($1.5\text{--}2.5\text{ MWh/t}$) | Closed-loop ($\ge 1,000\text{ yr}$) |
| **BECCS** | $500\text{--}2,000$ | $300,000\text{--}2,000,000$ | Arable land competition | Supply-chain LCA complexity |
| **SPAM-V** | $9,000\text{--}18,000$ | $100,000\text{--}500,000$ | Benthic diagenesis | Enclosed pit boundary |

### 1.2 The SPAM-V Paradigm: Enclosed Geological Instrumentation Meets High-Rate Marine Fixation

Marine microalgae exhibit photosynthetic carbon fixation rates $10\text{ to }20\text{ times}$ higher per unit area than terrestrial forests without requiring arable soil or freshwater. At realistic sustained outdoor productivities of $15\text{ to }25\text{ g dry weight (DW) m}^{-2}\text{ d}^{-1}$, a $1\text{ km}^2$ ($100\text{ ha}$) array of shallow coastal pools fixes $2,460\text{ to }4,100\text{ t C km}^{-2}\text{ yr}^{-1}$, equivalent to $9,000\text{ to }15,000\text{ tCO}_2\text{ km}^{-2}\text{ yr}^{-1}$ prior to downstream losses.

Historically, microalgal CDR failed because harvesting dilute algae ($0.3\text{--}1.0\text{ g DW L}^{-1}$) via mechanical centrifugation or thermal drying consumed more fossil energy than the algae captured, while synthetic fertilizers carried heavy embodied greenhouse gas burdens. SPAM-V eliminates these failure modes through four structural innovations:

1. **Ultra-Low-Head Coastal Plastic Pools:** Constructing shallow, geomembrane-lined pools on flat coastal land immediately adjacent to both the ocean and a deep coastal mine pit limits seawater intake and return pumping lifts to $\Delta H \approx 1\text{--}2\text{ m}$, reducing hydraulic electricity demand by over $98\%$.
2. **Agricultural Waste Nutrient Valorization:** Replacing energy-intensive synthetic Haber-Bosch fertilizers with treated agricultural waste (e.g., livestock anaerobic digestate, poultry/swine effluent, or agro-industrial runoff) supplies nitrogen ($\mathrm{N}$), phosphorus ($\mathrm{P}$), and trace elements at near-zero embodied manufacturing emissions while mitigating coastal eutrophication.
3. **In-Pond Flocculation and Clear-Water Decanting:** Rather than pumping millions of tonnes of dilute water into the mine pit, flocculants are dosed directly into the shallow coastal pools. Once the algae settles to the pool floor, the top $95\text{--}98\%$ of clarified seawater is decanted back to the ocean. Only the concentrated bottom algal sludge ($2\text{--}5\%$ solids) is transferred down into the adjacent mine pit, assisted by gravity.
4. **Periodic Sand Capping (Engineered Turbidites):** Deposited algal sludge in the deep center of the flooded mine pit is periodically covered with a thin broadcast layer of sand. In natural marine geology, rapid burial of organic mud beneath sandy turbidite flows produces the highest organic carbon preservation efficiencies on Earth. Replicating this mechanism inside an enclosed, instrumented mine void accelerates porewater expulsion, prevents resuspension, and isolates the organic carbon from oxygenated water.

### 1.3 Quantitative Scaling Potential: One Serious Pit vs. 1,000 Pits Globally

To evaluate the macro-scale significance of SPAM-V, we examine the capacity of a single commercial-scale mine-pit facility and a global network of $1,000$ pits:

* **Single Reasonably Large Pit Facility:**
  * **Annual Flux (Flow Rate of CDR):** Consider a commercial deployment coupling a $15\text{ km}^2$ ($1,500\text{ ha}$) array of shallow coastal plastic pools operating at a mean net productivity of $20\text{ g DW m}^{-2}\text{ d}^{-1}$ ($45\%$ carbon) with an adjacent coastal open-pit void. The pools fix $49,275\text{ t C yr}^{-1}$ ($180,675\text{ tCO}_2\text{ yr}^{-1}$ gross). After accounting for $90\%$ in-pond flocculation recovery, $78\%$ long-term climate-durable retention under sand capping, and lifecycle/process emission deductions, a single pit facility delivers $\approx 110,000\text{ to }125,000\text{ tCO}_2\text{ yr}^{-1}$ ($0.11\text{--}0.125\text{ MtCO}_2\text{ yr}^{-1}$) of net durable CDR, and up to $0.35\text{--}0.50\text{ MtCO}_2\text{ yr}^{-1}$ for larger sites paired with $40\text{--}50\text{ km}^2$ pond arrays.
  * **Cumulative Vault Capacity (Total Stock per Pit):** A reasonably large open-pit mine void has a total geometric volume of $50\text{ to }150\text{ Mm}^3$. Dedicating the bottom $30\text{ Mm}^3$ of the deep anoxic pit floor to alternating layers of consolidated algal mud and sand capping (where compacted algal-sand sediment holds $\approx 120\text{ kg C m}^{-3}$ of bulk wet volume) allows a single large mine pit to permanently store $3.6\text{ Mt C}$, equivalent to $\approx 13.2\text{ MtCO}_2$ ($13.2\text{ million tonnes of }\mathrm{CO_2}$) over its operational filling lifetime, with $100\text{ Mm}^3$ storage zones capable of holding more than $40\text{ MtCO}_2$.
* **Global Deployment Across 1,000 Mine Pits:**
  * Globally, tens of thousands of exhausted or closing open-pit mines exist, with well over $1,000$ large voids situated within coastal corridors, arid saline basins, or near-coastal transport distances.
  * Deploying SPAM-V across $1,000$ mine-pit facilities would remove $110\text{ to }500\text{ MtCO}_2\text{ yr}^{-1}$ ($0.11\text{ to }0.50\text{ gigatonnes of }\mathrm{CO_2}\text{ per year}$) on an ongoing basis, while providing a combined geological storage vault capacity of $13\text{ to }40\text{ GtCO}_2$ ($13\text{ to }40\text{ billion tonnes of }\mathrm{CO_2}$). This places a $1,000$-pit SPAM-V network on par with global mid-century targets for Direct Air Capture, at a fraction of the energy and capital cost.

---

## 2. Operational Architecture: The Eight-Stage Low-Head and Sand-Capping Cycle

Each operational iteration of the revised SPAM-V system executes an eight-stage physical sequence designed to minimize water lifting head, eliminate mechanical dewatering, keep excess water out of the mine pit, and mechanically lock carbon on the pit floor.

```text
[1. Low-Head Seawater Intake (~1m lift)] 
       |
       v
[2. Shallow Plastic Pool + Agricultural Waste Nutrients (Days 1-14 Bloom)]
       |
       v
[3. In-Pool Flocculation (Algae settles to plastic pool floor; clear water on top)]
       |
       +---> [4. Low-Head Decant (~1m head): 95-98% Clear Water Returned to Sea]
       |
       v
[5. Bottom Algal Sludge Extracted & Gravity-Flushed to Deep Center of Nearby Pit]
       |
       v
[6. Deep Stratified Settling to Anoxic Pit Floor (No pit overflow)]
       |
       v
[7. Periodic Sand Broadcast ("Engineered Turbidite" Compaction & Gas Seal)]
       |
       v
[8. Continuous Biogeochemical Monitoring & Cycle Repeat]
```

### Stage 1: Low-Head Seawater Intake into Shallow Coastal Plastic Pools

Modular, shallow cultivation pools ($h = 0.30\text{ to }0.50\text{ m}$ depth) are constructed on flat coastal land located immediately between the ocean and the rim of the mine pit. The pools are built using low-cost earth berms lined with heavy-duty, UV-stabilized high-density polyethylene (HDPE) or linear low-density polyethylene (LLDPE) plastic geomembranes. Because the pools sit just above high-tide sea level, axial-flow coastal pumps lift raw filtered seawater against a total static and friction head of only $\Delta H_{\mathrm{in}} \approx 1.0\text{ to }1.5\text{ m}$. Roughly $5\%$ of the previous cycle's settled algal culture is retained in the bottom sump to serve as the living inoculum ($X_0$).

### Stage 2: Agricultural Waste Nutrient Dosing and Photosynthetic Bloom

To avoid the high lifecycle greenhouse gas footprint of synthetic fertilizers, the seawater is dosed with pre-screened, nutrient-rich agricultural waste—such as liquid anaerobic digestate, clarified livestock/poultry manure effluent, or agricultural drainage rich in ammonium ($\mathrm{NH_4^+}$), nitrate ($\mathrm{NO_3^-}$), and orthophosphate ($\mathrm{PO_4^{3-}}$). Over a 14-day active growth phase ($t_g$), solar irradiance and gentle paddlewheel or air-lift circulation drive rapid microalgal division. As photosynthesis consumes dissolved inorganic carbon ($DIC$), pond $pH$ rises ($pH\ 8.5\text{--}9.5$), lowering aqueous $p\mathrm{CO_2}$ well below atmospheric equilibrium and drawing atmospheric $\mathrm{CO_2}$ across the shallow water surface.

### Stage 3: In-Pool Flocculation and Gravity Settling

At the end of the growth phase (when standing biomass reaches $X_f \approx 0.5\text{ to }1.0\text{ g DW L}^{-1}$), circulation is halted and the shallow plastic pool is dosed directly with a low-toxicity flocculant (e.g., cationic biopolymers, magnesium/calcium hydroxide triggered by high-$pH$ auto-flocculation, or fine mineral coagulant aids). Within $2\text{ to }6\text{ hours}$, the individual microalgal cells aggregate into dense flocs and settle directly onto the smooth plastic floor of the shallow pool, forming a concentrated benthic algal blanket ($\approx 20\text{ to }40\text{ g DW L}^{-1}$, or $2\text{--}4\%$ solids) beneath a layer of clarified seawater.

### Stage 4: Low-Head Clear-Water Decanting Back to the Sea

Once the algal blanket has settled to the bottom $1\text{ to }2\text{ cm}$ of the pool, floating surface skimmers or side-wall decant weirs draw off the top $95\text{ to }98\%$ of clarified, algae-free seawater and return it directly to the ocean. Because the pool is at coastal elevation, this return flows largely by gravity or requires at most $\approx 1.0\text{ m}$ of low-head pumping to clear coastal outfalls. This step is foundational: by returning more than $95\%$ of the water directly from the pool back to the sea, the mine pit never receives massive volumes of water, completely preventing pit overflow ("the bathtub problem") and avoiding water-column turbulence ("the blender effect").

### Stage 5: Concentrated Sludge Transfer Toward the Center of the Pit

With the clear water removed, only the thick algal sludge remains on the smooth, slightly sloped plastic floor of the pool. A small volume of flush water or a low-power positive-displacement/slurry pump pushes this concentrated algal paste out of the pool's bottom sump into a transfer pipe leading into the adjacent mine pit. Because the floor of the mine pit lies $100\text{ to }200\text{ m}$ below the elevation of the coastal pools, gravity provides the driving head. The discharge pipe extends along a submerged tether or inclined guide to inject the dense algal slurry directly toward the deepest geometric center of the pit below the chemocline, preventing the sludge from coating shallow pit walls where sunlight or oxygen could degrade it.

### Stage 6: Deep Benthic Accumulation in the Stratified Pit

Inside the permanently flooded mine pit, the injected algal slurry settles into the central benthic depression. Because only a small volume of dense slurry enters the pit each cycle, the pit's vertical density stratification (an oxygenated upper layer separated by a sharp pycnocline/chemocline from a cold, hypersaline, anoxic bottom layer) remains undisturbed. Any small excess volume of displaced water in the pit is passively bled off from the clean surface layer over a weir or evaporated.

### Stage 7: Periodic Sand Spreading (Engineered Turbidite Capping)

After one or more sludge deposition cycles, a barge, slurry spreader, or pneumatic broadcaster distributes a thin, uniform layer of sand ($1\text{ to }5\text{ cm}$ thick, sourced from coastal silica/carbonate sand or benign mine overburden fines) across the center of the pit. Having a specific gravity of $\approx 2.65$, the sand grains rain rapidly through the water column and settle evenly over the soft algal mud layer. This periodic sand cap performs four critical engineering functions:

1. **Surcharge Consolidation:** The heavy sand layer acts as a permeable piston, pressing down on the low-density algal mud, expelling trapped porewater upward through the sand pores, and compressing the underlying algae into a dense, low-permeability organic lamina.
2. **Physical Anti-Resuspension Shield:** The sand forms a heavy armor layer that prevents bottom currents or gas bubbles from resuspending the fine algal particles into the water column.
3. **Diffusive Tortuosity Barrier:** Alternating layers of compacted algal mud and sand create a laminated sediment stack ("engineered turbidites") that increases diffusive path lengths ($L_{\mathrm{eff}}$), slowing the upward escape of dissolved inorganic carbon ($DIC$), dissolved organic carbon ($DOC$), and dissolved methane ($\mathrm{CH_4}$).
4. **Geochemical Bio-Filter:** Incorporating iron-bearing sands or carbonate sands provides reactive mineral surfaces and terminal electron acceptors that stimulate Anaerobic Oxidation of Methane (AOM) within the cap matrix before dissolved $\mathrm{CH_4}$ can reach the open water column.

### Stage 8: Reset and Continuous Carbon-Fate Verification

Immediately after the bottom sludge is evacuated from the coastal plastic pool (retaining a $5\%$ residual volume as inoculum), the pool is refilled with fresh seawater (Stage 1) to initiate the next 14-day bloom. Concurrently, automated sensor arrays in the ponds, decant outfalls, and pit water column log carbon, nutrient, and greenhouse gas fluxes to verify net atmospheric removal.

---

## 3. Reconciled Nomenclature, Mass Balance, and Low-Head Energetics

### 3.1 Reconciling Concentration, Areal Productivity, and Sludge Dewatering

To ensure strict mathematical closure across all eight stages, four distinct biomass metrics are defined and linked.

**Initial and Final In-Pond Concentrations ($X_0, X_f$, in $\mathrm{g\ DW\ L^{-1}}$):** In a shallow pool of depth $h$ ($\mathrm{m}$), active growth window $t_g$ ($\mathrm{d}$), net areal dry-weight productivity $P_X$ ($\mathrm{g\ DW\ m^{-2}\ d^{-1}}$), and retained inoculum fraction $r$:

$$\Delta X = X_f - X_0 = \frac{P_X \cdot t_g}{1000 \cdot h}, \qquad X_f = \frac{P_X \cdot t_g}{1000 \cdot h (1 - r)}, \qquad X_0 = r X_f$$

For a shallow plastic pool of depth $h = 0.30\text{ m}$, $P_X = 18.0\text{ g DW m}^{-2}\text{ d}^{-1}$, $t_g = 14\text{ d}$, and $r = 0.05$:

$$\Delta X = \frac{18.0 \times 14}{300} = 0.840\text{ g DW L}^{-1}, \qquad X_f = \frac{0.840}{0.95} = 0.884\text{ g DW L}^{-1}, \qquad X_0 = 0.044\text{ g DW L}^{-1}$$

**In-Pond Flocculation and Decant Concentration Factor:** During Stages 3 and 4, fraction $\eta_H$ (e.g., $0.90$) of the suspended biomass settles into the bottom sludge volume fraction $f_{\mathrm{sludge}}$ (e.g., $f_{\mathrm{sludge}} = 0.03$, meaning $97\%$ of the pool volume is decanted back to the sea as clarified water). The concentration of the bottom algal sludge pushed into the pit ($X_{\mathrm{sludge}}$) is:

$$X_{\mathrm{sludge}} = \frac{\eta_H (1 - r) X_f}{f_{\mathrm{sludge}}} = \frac{0.90 \times 0.95 \times 0.884}{0.03} \approx 25.2\text{ g DW L}^{-1}\quad (2.52\%\text{ dry solids})$$

**Cycle Turnaround and Annualized Carbon Delivery ($C_{\mathrm{deposited,yr}}$, in $\mathrm{t\ C\ yr^{-1}}$):** With $t_g = 14\text{ d}$ and $t_{\mathrm{turnaround}} = 1\text{ d}$ (6 hours settling, 8 hours decanting, 4 hours sludge flushing, 6 hours refilling), total cycle duration is $t_{\mathrm{cycle}} = 15\text{ d}$ ($N_{\mathrm{cycles}} = 24.33\text{ yr}^{-1}$, active growth duty cycle $\delta = 14/15 = 93.3\%$). For total pond area $A$ ($\mathrm{m^2}$), biomass carbon fraction $f_C$, and pit-center delivery efficiency $\eta_D$:

$$C_{\mathrm{deposited,yr}} = A \cdot P_X \cdot f_C \cdot t_g \cdot N_{\mathrm{cycles}} \cdot \eta_H \cdot \eta_D \cdot 10^{-6}$$

### 3.2 Hydraulic Energy Proof: Why 1-Meter Plastic Pools Transform the Energy Ledger

In an inland whole-culture transfer design, pumping $1\text{ m}^3$ of dilute culture ($0.84\text{ g DW L}^{-1}$) over $40\text{ km}$ against $220\text{ m}$ of dynamic head requires $\approx 0.80\text{ kWh m}^{-3}$, or $2,116\text{ kWh per tonne of carbon}$ ($\approx 0.53\text{ tCO}_2\text{e emitted per t C}$ on a $0.25\text{ tCO}_2\text{e MWh}^{-1}$ grid—consuming nearly $15\%$ of gross captured $\mathrm{CO_2}$ in pumping alone).

Under the Low-Head Coastal Plastic Pool and In-Pond Decant design:

1. **Seawater Intake Lift ($\Delta H_{\mathrm{in}} = 1.2\text{ m}$):** Lifting $1\text{ m}^3$ of seawater into the shallow pool at pump efficiency $\eta_p = 0.75$ requires:

$$e_{\mathrm{in}} = \frac{\rho g \Delta H_{\mathrm{in}}}{3.6 \times 10^6 \cdot \eta_p} = \frac{1025 \times 9.81 \times 1.2}{3.6 \times 10^6 \times 0.75} = 0.00447\text{ kWh m}^{-3}$$

2. **Clear-Water Decant Return ($\Delta H_{\mathrm{out}} = 1.0\text{ m}$):** Pumping or assisting the $97\%$ clarified water back to the sea requires $e_{\mathrm{out}} = 0.00372\text{ kWh m}^{-3}$ (or $0\text{ kWh m}^{-3}$ if gravity-drained at low tide).
3. **Bottom Sludge Push into Adjacent Pit ($\Delta H_{\mathrm{sludge}} \le 2.0\text{ m}$ friction head, gravity-assisted):** Moving the $3\%$ sludge volume requires $0.03 \times 0.0074 = 0.00022\text{ kWh m}^{-3}$ of original pond volume.

Summing all three steps, total hydraulic energy is $0.0084\text{ kWh per m}^3$ of pond volume—translating to $24.8\text{ kWh per tonne of delivered carbon}$ ($\approx 6.8\text{ kWh per tCO}_2\text{ gross}$). This represents a $98.8\%$ reduction in pumping energy, cutting hydraulic process emissions to less than $0.2\%$ of gross captured $\mathrm{CO_2}$.

### 3.3 Agricultural Waste Stoichiometry and Counterfeit-Carbon Accounting

Using agricultural waste (e.g., livestock manure digestate or agricultural runoff) as the nutrient source introduces two mandatory accounting rules in the SPAM-V ledger:

1. **Exclusion of Allochthonous Agricultural Organic Carbon ($C_{\mathrm{ag,org}}$):** Agricultural waste contains both inorganic nutrients ($\mathrm{NH_4^+, NO_3^-, PO_4^{3-}}$) and dissolved/particulate organic carbon ($C_{\mathrm{ag,org}}$) that was originally fixed by terrestrial crops. Simply dumping agricultural organic carbon into a pit is waste disposal, not new marine algal atmospheric fixation. Therefore, the total carbon entering the pool via agricultural waste ($F_{C,\mathrm{ag}}$) is measured prior to dosing and explicitly subtracted from newly fixed autotrophic algal carbon ($C_{\mathrm{fixed,autotrophic}}$):

$$C_{\mathrm{fixed,autotrophic}} = \Delta C_{\mathrm{pond,total}} - C_{\mathrm{ag,retained}}$$

Furthermore, if aerobic bacteria in the shallow pool respire a fraction of $C_{\mathrm{ag,org}}$ into aqueous $\mathrm{CO_2}$ that the algae subsequently refix, isotopic ($\delta^{13}\mathrm{C}$) and carbon-budget closure ensure that only net atmospheric $\mathrm{CO_2}$ invasion (plus verified counterfactual avoidance of terrestrial agricultural methane or $\mathrm{N_2O}$ emissions, if separately credited) is counted toward $\Delta M_{\mathrm{CO_2}}(t)$.

2. **Nitrification/Denitrification Nitrous Oxide ($\mathrm{N_2O}$) Penalty:** Adding high-ammonium agricultural waste to warm coastal ponds can stimulate microbial nitrification and denitrification, producing nitrous oxide ($\mathrm{N_2O}$, where $\mathrm{GWP}_{100} \approx 273$). The emission factor $EF_{\mathrm{N_2O}}$ ($\mathrm{kg\ N_2O\text{-}N}$ emitted per $\mathrm{kg\ N}$ applied) is continuously measured via floating gas chambers and deducted directly in the climate forcing ledger ($\dot{E}_{\mathrm{non\text{-}CO_2}, H}$).

---

## 4. Geomechanical and Geochemical Physics of Periodic Sand Capping

Spreading a thin layer of sand ($h_{\mathrm{sand}} = 1\text{ to }5\text{ cm}$) over each deposited batch of algal sludge at the center of the pit transforms loose organic floc into a geologically stable sedimentary deposit through three quantifiable mechanisms.

### 4.1 Surcharge-Driven Terzaghi Consolidation and Porewater Expulsion

Freshly settled algal flocs have a high water content ($\phi_0 \approx 0.95\text{--}0.97$) and near-zero effective stress ($\sigma'_v \approx 0$), making them susceptible to resuspension. When quartz or carbonate sand ($\rho_s \approx 2,650\text{ kg m}^{-3}$, bulk submerged unit weight $\gamma'_{\mathrm{sand}} = (1 - \phi_{\mathrm{sand}})(\rho_s - \rho_w)g \approx 9.8\text{ kN m}^{-3}$) is spread over the algal layer, it imposes an immediate vertical effective surcharge stress $\Delta \sigma'_v = \gamma'_{\mathrm{sand}} h_{\mathrm{sand}}$.

According to one-dimensional Terzaghi consolidation theory:

$$\frac{\partial u_e}{\partial t} = c_v \frac{\partial^2 u_e}{\partial z^2}, \qquad c_v = \frac{k_v}{\rho_w g m_v}$$

where $u_e$ is excess porewater pressure, $k_v$ is vertical hydraulic conductivity, and $m_v$ is the coefficient of volume compressibility. Because the sand layer is highly permeable ($k_{v,\mathrm{sand}} \sim 10^{-4}\text{ m s}^{-1}$) relative to the compressing algal mud ($k_{v,\mathrm{mud}} \sim 10^{-8}\text{ m s}^{-1}$), each sand layer acts as a horizontal drainage blanket. Porewater squeezed out of the underlying algal layer drains rapidly into the sand interbeds, decreasing the void ratio $e$ of the algal layer, increasing its shear strength $\tau_f = c' + \sigma'_v \tan \phi'$, and reducing its vertical permeability by orders of magnitude.

### 4.2 Diffusive Tortuosity and Multi-Layer Turbidite Trapping

In a stacked sequence of $N$ alternating algal-mud layers (thickness $d_m$, porosity $\phi_m$) and sand-cap layers (thickness $d_s$, porosity $\phi_s$), upward molecular diffusion of dissolved remineralization products ($DIC, DOC, \mathrm{CH_4}$) is governed by Fick's First Law with effective sediment diffusivity $D_{\mathrm{eff}} = (\phi / \theta^2) D_0$ (where $\theta^2 \approx 1 - 2\ln(\phi)$ is geometric tortuosity):

$$J_{\mathrm{upward}} = - D_{\mathrm{eff,harmonic}} \frac{\Delta C}{\sum_{k=1}^N (d_{m,k} + d_{s,k})}$$

As surcharge consolidation compresses $\phi_m$ from $0.96$ down to $0.60\text{--}0.70$, tortuosity increases sharply, trapping dissolved carbon in the deep porewater.

### 4.3 Suppression of Ebullition (Bubble Venting) and Stimulation of AOM

The greatest climate risk in benthic organic storage is methane ebullition—where dissolved $\mathrm{CH_4}$ concentrations exceed hydrostatic solubility ($C_{\mathrm{sat}}(P, T, S)$), forming gas bubbles that punch through the sediment and rise rapidly to the atmosphere, bypassing water-column oxidation.

1. **Hydrostatic Solubility Ceiling:** At the center of a $180\text{ m}$ deep flooded pit ($P \approx 19\text{ atm}$), methane solubility is $\approx 19\times$ higher than at the surface ($\sim 25\text{--}30\text{ mmol CH}_4\text{ L}^{-1}$), suppressing bubble nucleation.
2. **Cap Capillary Entry Pressure:** A compacted sand-silt cap provides a mechanical capillary barrier and distributes upward gas migration into slow dissolved diffusion rather than localized bubble conduits.
3. **Sulfate- and Iron-Mediated Anaerobic Oxidation of Methane (AOM):** By mixing seawater (containing $28\text{ mM SO}_4^{2-}$) and reactive iron/manganese oxide minerals into the sand cap, upward-diffusing $\mathrm{CH_4}$ encounters a permanent Sulfate-Methane Transition Zone (SMTZ) inside the sand cap:

$$\mathrm{CH_4} + \mathrm{SO_4^{2-}} \longrightarrow \mathrm{HCO_3^-} + \mathrm{HS^-} + \mathrm{H_2O}$$

$$\mathrm{CH_4} + 8\mathrm{Fe(OH)_3} + 15\mathrm{H^+} \longrightarrow \mathrm{HCO_3^-} + 8\mathrm{Fe^{2+}} + 21\mathrm{H_2O}$$

This converts high-GWP methane into alkalinity ($\mathrm{HCO_3^-}$) and precipitates insoluble carbonate and iron-sulfide ($\mathrm{FeS_2}$, pyrite) minerals directly inside the sand cap.

---

## 5. System Architecture: The State-Flux Matrix and Decoupled Climate Ledger

### 5.1 The Foundational Distinction

The SPAM-V mathematical spine enforces a strict separation among three physical and accounting quantities:

$$\mathrm{Vault\ Storage}\ (C_{\mathrm{vault}}) \;\neq\; \mathrm{Atmospheric\ CO_2\ Removal}\ (\Delta M_{\mathrm{CO_2}}) \;\neq\; \mathrm{Net\ Climate\ Impact}\ (\Delta \mathcal{C}_{H})$$

### 5.2 The Pool by Destination State-Flux Matrix

Every carbon atom entering or fixed within the facility is tracked across a non-overlapping state matrix $\mathbf{C}_{i,j}(t)$ ($\mathrm{t\ C}$) and directed flux tensor $\mathbf{F}_{ij \rightarrow kl}(t)$ ($\mathrm{t\ C\ yr^{-1}}$):

* **Carbon Chemical Pools ($i, k$):**
  $$i \in \{POC_{\mathrm{bio}}, POC_{\mathrm{det}}, POC_{\mathrm{ag}}, DOC, DIC, \mathrm{CH_4}, \mathrm{CO_2(g)}, PIC_{\mathrm{mineral}}\}$$
* **Physical Destinations ($j, l$):**
  $$j \in \{\mathrm{pool}, \mathrm{decant\text{-}sea}, \mathrm{vault\text{-}sed}, \mathrm{vault\text{-}water}, \mathrm{gw}, \mathrm{atm}\}$$

The conservation differential equation for any state cell $(i,j)$ is:

$$\frac{dC_{i,j}}{dt} = \sum_{k,l} F_{kl \rightarrow ij}(t) - \sum_{k,l} F_{ij \rightarrow kl}(t) + R_{i,j}(\mathbf{C}, \mathbf{z}_j, \boldsymbol{\theta})$$

where $R_{i,j}$ represents internal biogeochemical phase transformations (photosynthesis, respiration, sulfate reduction, methanogenesis, AOM, and authigenic carbonate precipitation) governed by the local environmental state vector:

$$\mathbf{z}_j(t) = [O_2, pH, Eh, T, S, \mathrm{NH_4^+}, \mathrm{NO_3^-}, \mathrm{PO_4^{3-}}, \mathrm{SO_4^{2-}}, \mathrm{H_2S}, \mathrm{Fe^{2+}}, TA, \mathbf{u}_{\mathrm{flow}}, \phi, \sigma'_v]$$

### 5.3 Dimensionally Consistent Climate Ledger and Sign Conventions

**Explicit Sign Convention:** Across all equations, $\Delta M_{\mathrm{CO_2}} > 0$ and $\Delta \mathcal{C}_H > 0$ denote net removal of greenhouse gases from the atmosphere (net climate cooling benefit), whereas negative values denote net warming emissions.

**1. Counterfactual Atmospheric $\mathrm{CO_2}$ Mass Reduction ($\Delta M_{\mathrm{CO_2}}(t)$, in $\mathrm{t\ CO_2}$):**

$$\Delta M_{\mathrm{CO_2}}(t) = M_{\mathrm{atm,CO_2}}^{\mathrm{CF}}(t) - M_{\mathrm{atm,CO_2}}^{\mathrm{SPAM}}(t) = \frac{44}{12} \int_0^t \left[ F_{C,\mathrm{atm}}^{\mathrm{CF}}(\tau) - F_{C,\mathrm{atm}}^{\mathrm{SPAM}}(\tau) \right] d\tau$$

where $F_{C,\mathrm{atm}}$ ($\mathrm{t\ C\ yr^{-1}}$) is the net surface-to-atmosphere carbon flux integrated across the coastal plastic pools, the coastal ocean receiving the decanted water, and the mine pit surface.

**2. Horizon-Integrated Net Climate Impact ($\Delta \mathcal{C}_{H_{\mathrm{assess}}, H_{\mathrm{GWP}}}$, in $\mathrm{t\ CO_2e}$):**
Evaluated at assessment horizon $H_{\mathrm{assess}} \in \{10, 100, 500\text{ yr}\}$ using declared Global Warming Potential horizon $H_{\mathrm{GWP}} \in \{20, 100\text{ yr}\}$:

$$\Delta \mathcal{C}_{H_{\mathrm{assess}}, H_{\mathrm{GWP}}} = \Delta M_{\mathrm{CO_2}}(H_{\mathrm{assess}}) - \int_0^{H_{\mathrm{assess}}} \left[ \dot{E}_{\mathrm{process}}(\tau) + \dot{E}_{\mathrm{LC}}(\tau) + \dot{E}_{\mathrm{non\text{-}CO_2}, H_{\mathrm{GWP}}}(\tau) \right] d\tau$$

where every term is strictly in $\mathrm{t\ CO_2e}$:
* $\dot{E}_{\mathrm{process}}(t)$ ($\mathrm{t\ CO_2e\ yr^{-1}}$): Emissions from $1\text{ m}$ seawater intake pumping, decant return, paddlewheel mixing, sludge transfer, and sand spreading.
* $\dot{E}_{\mathrm{LC}}(t)$ ($\mathrm{t\ CO_2e\ yr^{-1}}$): Amortized embodied emissions of the HDPE/LLDPE plastic pool liners, piping, flocculant chemicals, agricultural waste transport, and sand excavation/delivery.
* $\dot{E}_{\mathrm{non\text{-}CO_2}, H_{\mathrm{GWP}}}(t)$ ($\mathrm{t\ CO_2e\ yr^{-1}}$): Direct non-$\mathrm{CO_2}$ biogenic gas fluxes escaping to the atmosphere from both the coastal pools (e.g., $\mathrm{N_2O}$ from agricultural waste nitrogen) and the mine pit surface ($\mathrm{CH_4}$ and $\mathrm{N_2O}$):

$$\dot{E}_{\mathrm{non\text{-}CO_2}, H_{\mathrm{GWP}}}(t) = \dot{M}_{\mathrm{CH_4,atm}}^{\mathrm{emitted}}(t) \cdot \mathrm{GWP}_{\mathrm{CH_4}, H_{\mathrm{GWP}}} + \dot{M}_{\mathrm{N_2O,atm}}^{\mathrm{emitted}}(t) \cdot \mathrm{GWP}_{\mathrm{N_2O}, H_{\mathrm{GWP}}}$$

---

## 6. Master Causal Sequence, Break-Even Productivity, and Bayesian Inference

### 6.1 Partitioned Master Sequence (Direct Facility Measurement vs. Counterfactual Inference)

To prevent overclaiming what pit measurements alone prove, the master causal sequence separates the Directly Measured Facility Domain (Domain A) from the Model-Inferred Counterfactual Domain (Domain B):

* **Domain A (Directly Measured and Isotopically Constrained Facility Mass Balance):**

$$P_{C,\mathrm{auto}} \longrightarrow C_{\mathrm{sludge}} \longrightarrow C_{\mathrm{deposited}} \longrightarrow \mathbf{C}_{i,\mathrm{vault}}(t), \mathbf{F}_{\mathrm{vault}\rightarrow \mathrm{water/gw/atm}}(t)$$

* **Domain B (Counterfactual Air-Sea and Climate Model):**

$$\mathbf{F}_{\mathrm{vault}\rightarrow \mathrm{water/gw/atm}}(t) + \Delta DIC_{\mathrm{decant}} \longrightarrow \Delta F_{\mathrm{air\text{-}sea}} \longrightarrow \Delta M_{\mathrm{CO_2}}(t) \longrightarrow \Delta \mathcal{C}_H$$

* **Why Decanting Clear Water Back to the Sea Helps Domain B:** When photosynthesis depletes $DIC$ in the shallow pool and the clarified, $DIC$-depleted, high-$pH$ water is decanted back into the coastal surface ocean (Stage 4), that parcel of seawater retains its carbonate deficit ($\Delta DIC < 0$, elevated $[\mathrm{CO_3^{2-}}]$) and continues absorbing atmospheric $\mathrm{CO_2}$ across the coastal ocean surface even if gas equilibration inside the shallow pool was incomplete during the 14-day bloom.

### 6.2 Positive-Performance Set and Break-Even Productivity ($P_{C,\mathrm{BE},H}$)

Let $\boldsymbol{\Theta} = (\boldsymbol{\theta}, \mathbf{X}, \mathbf{u})$ denote the joint uncertain state comprising biogeochemical/geotechnical parameters $\boldsymbol{\theta}$, ecological community vector $\mathbf{X} = [X_{\mathrm{algae}}, X_{\mathrm{bacteria}}, X_{\mathrm{grazers}}, X_{\mathrm{pathogens}}]$, and seasonal environmental forcing $\mathbf{u}$. The positive-performance set is:

$$\mathcal{P}_+(\boldsymbol{\Theta}) = \left\{ P_{C,\mathrm{auto}} : \Delta \mathcal{C}_{H_{\mathrm{assess}}, H_{\mathrm{GWP}}}(P_{C,\mathrm{auto}}, \boldsymbol{\Theta}) > 0 \right\}$$

The CDR Break-Even Productivity is the infimum of this set:

$$P_{C,\mathrm{BE},H}(\boldsymbol{\Theta}) = \inf \mathcal{P}_+(\boldsymbol{\Theta}) \quad \text{if } \mathcal{P}_+(\boldsymbol{\Theta}) \neq \varnothing$$

Because pumping energy in the $1\text{ m}$ plastic-pool and in-pond decant architecture is nearly zero and agricultural waste replaces synthetic fertilizer, $P_{C,\mathrm{BE},H}$ is substantially lower than in high-head whole-culture designs—shifting the primary feasibility hurdle from pumping energy to pond ecological stability and sand-capped benthic methane suppression.

### 6.3 Bayesian Posterior Propagation

The final decision metric is the posterior probability distribution of net climate benefit conditioned on all experimental observations $D$:

$$p(\Delta \mathcal{C}_H \mid D) = \int p(\Delta \mathcal{C}_H \mid \boldsymbol{\Theta}) \, p(\boldsymbol{\Theta} \mid D) \, d\boldsymbol{\Theta}$$

---

## 7. Reference Numerical Mass and Climate Balance (Single-Pit vs. 1,000-Pit Baseline)

The table below provides the static reference calculations for the Low-Head Plastic Pool and Sand-Capping architecture under baseline parameters ($P_X = 18.0\text{ g DW m}^{-2}\text{ d}^{-1}$, active duty cycle $\delta = 93.3\%$, carbon fraction $f_C = 0.45$, in-pool flocculation recovery $\eta_H = 0.90$, 100-year sand-capped durable retention $S_{\mathrm{atm},100} = 0.78$, unoxidized methane escape $= 0.5\%$ of deposited carbon at $\mathrm{GWP}_{100} = 28$, and agricultural-waste $\mathrm{N_2O}$ factor $= 0.8\%$ of applied $\mathrm{N}$):

| Ledger Component | Standard Pit ($10\text{ km}^2$ Pools) | Large Pit ($25\text{ km}^2$ Pools) | 1,000-Pit Network ($10\text{ km}^2$ avg) |
| :--- | :--- | :--- | :--- |
| **Gross Autotrophic Carbon Fixed** | $27,590\text{ t C/yr}$ | $68,975\text{ t C/yr}$ | $27.59\text{ Mt C/yr}$ |
| **Gross Stoichiometric $\mathrm{CO_2}$** | $101,163\text{ tCO}_2\text{/yr}$ | $252,908\text{ tCO}_2\text{/yr}$ | $101.16\text{ MtCO}_2\text{/yr}$ |
| **Carbon in Bottom Sludge ($\eta_H = 90\%$)** | $24,831\text{ t C/yr}$ | $62,078\text{ t C/yr}$ | $24.83\text{ Mt C/yr}$ |
| **100-Yr Retained $\mathrm{CO_2}$ ($S_{\mathrm{atm}} = 78\%$)** | $71,017\text{ tCO}_2\text{/yr}$ | $177,542\text{ tCO}_2\text{/yr}$ | $71.02\text{ MtCO}_2\text{/yr}$ |
| **Low-Head $1\text{ m}$ Pumping Deduction** | $-138\text{ tCO}_2\text{e/yr}$ | $-345\text{ tCO}_2\text{e/yr}$ | $-0.14\text{ MtCO}_2\text{e/yr}$ |
| **Liner, Flocculant and Sand LCA** | $-2,980\text{ tCO}_2\text{e/yr}$ | $-7,449\text{ tCO}_2\text{e/yr}$ | $-2.98\text{ MtCO}_2\text{e/yr}$ |
| **Ag-Waste $\mathrm{N_2O}$ Deduction** | $-1,435\text{ tCO}_2\text{e/yr}$ | $-3,588\text{ tCO}_2\text{e/yr}$ | $-1.44\text{ MtCO}_2\text{e/yr}$ |
| **Unoxidized Pit $\mathrm{CH_4}$ Deduction** | $-4,635\text{ tCO}_2\text{e/yr}$ | $-11,588\text{ tCO}_2\text{e/yr}$ | $-4.64\text{ MtCO}_2\text{e/yr}$ |
| **Net Durable CDR ($\Delta \mathcal{C}_{100}$)** | $61,829\text{ tCO}_2\text{e/yr}$ | $154,572\text{ tCO}_2\text{e/yr}$ | $61.83\text{ MtCO}_2\text{e/yr}$ |

*Note on Scaling:* Across $1,000$ pits ranging between the Standard Pit configuration ($10\text{ km}^2$ pools) and the Large Pit configuration ($25\text{--}50\text{ km}^2$ pools), total global net durable CDR spans $62\text{ to }310\text{ MtCO}_2\text{e yr}^{-1}$ ($0.06\text{ to }0.31\text{ GtCO}_2\text{e yr}^{-1}$).

---

## 8. The Eight Falsifiable Experimental Gates

To transition the low-head plastic-pool and sand-capped pit architecture from a pre-feasibility concept to a certified CDR methodology, the system must sequentially pass eight quantitative experimental gates:

| Gate | Focus Area | Target Threshold | Primary Failure Mode |
| :--- | :--- | :--- | :--- |
| **Gate 0** | Site Qualification | $L \le 3\text{ km}$, $D \ge 100\text{ m}$, $Q_{\mathrm{gw,out}} \approx 0$ | Groundwater carbon escape |
| **Gate 1** | Ag-Waste Bloom Stability | $P_{C,\mathrm{auto}} \in \mathcal{P}_+(\boldsymbol{\Theta})$ | Rotifer/pathogen crash |
| **Gate 2** | In-Pool Floc and Decant | $\eta_H \ge 0.85$, $f_{\mathrm{sludge}} \le 0.03$ | Poor settling or HABs |
| **Gate 3** | Ag-Carbon and $\mathrm{N_2O}$ Audit | $\dot{E}_{\mathrm{N_2O}} \le 0.05\,\mathrm{Gross\ CO_2}$ | Counting manure C as CDR |
| **Gate 4** | Low-Head Sludge Transfer | $e_{\mathrm{hyd}} \le 25\text{ kWh/tC}$, $\eta_D \ge 0.95$ | Chemocline disruption |
| **Gate 5** | Sand-Cap Diagenesis | $\mathbf{F}_{\mathrm{unresolved}} \le 0.05$, $\mathrm{CH_4} \le 1\%$ | Bubble ebullition through cap |
| **Gate 6** | Air-Sea Attribution | $\Delta M_{\mathrm{CO_2}}(t) > 0$ | Incomplete air-sea invasion |
| **Gate 7** | Integrated Net CDR | $P(\Delta \mathcal{C}_{100} > 0) \ge 0.95$, $Q_{0.05} > 0$ | Net warming from $\mathrm{CH_4}$ or $\mathrm{N_2O}$ |

1. **Gate 0 (Coastal Pit and Site Qualification):** Verify that the candidate pit sits within $3\text{ km}$ of flat coastal land, extends deeper than $100\text{ m}$ below sea level, is geotechnically stable under rapid wetting/loading, and acts as an inward hydraulic sink ($Q_{\mathrm{gw,out}} \approx 0$).
2. **Gate 1 (Ag-Waste Bloom and Cyclic Stability):** Demonstrate that shallow plastic pools dosed with clarified agricultural waste sustain $P_{C,\mathrm{auto}} \in \mathcal{P}_+(\boldsymbol{\Theta})$ across repeated cycles without pathogen, rotifer, or ammonia-toxicity collapse ($p(\mathbf{X}_n \mid \mathbf{u}_n) \rightarrow p^*$).
3. **Gate 2 (In-Pool Flocculation and Decant Quality):** Confirm that in-pool flocculation settles $\eta_H \ge 0.85\text{--}0.90$ of biomass into a $\le 3\%$ bottom volume within $6\text{ hours}$, while the $97\%$ decanted seawater returned to the ocean satisfies coastal discharge standards for $\mathrm{N, P}$, $DO$, turbidity, and HAB toxins.
4. **Gate 3 (Allochthonous Carbon and $\mathrm{N_2O}$ Audit):** Using $\delta^{13}\mathrm{C}$ and $\Delta DIC/TA$ budgets, partition newly fixed autotrophic algal carbon from residual agricultural organic carbon, and verify that pond $\mathrm{N_2O}$ emissions remain below $5\%$ of gross captured $\mathrm{CO_2e}$.
5. **Gate 4 (Low-Head Hydraulic and Center-Pit Placement):** Demonstrate that $1\text{ m}$ seawater intake, decant return, and gravity-assisted bottom-sludge flushing place $\eta_D \ge 0.95$ of the sludge into the deep center of the pit without disturbing the upper chemocline or exceeding $25\text{ kWh tC}^{-1}$.
6. **Gate 5 (Sand-Capped Turbidite Diagenesis):** In $^{13}\mathrm{C}$-labeled benthic chambers, verify that periodic sand capping ($1\text{--}5\text{ cm}$) increases effective stress $\sigma'_v$, reduces upward $DIC/DOC$ diffusion, and suppresses $\mathrm{CH_4}$ ebullition and diffusive escape so that $\mathbf{F}_{\mathrm{unresolved}} \le 0.05$.
7. **Gate 6 (Counterfactual Air-Sea Attribution):** Combining pool air-water $\mathrm{CO_2}$ invasion measurements with coastal hydrodynamic modeling of the $DIC$-depleted decant plume, demonstrate a statistically verified positive atmospheric drawdown $\Delta M_{\mathrm{CO_2}}(t) > 0$.
8. **Gate 7 (Probabilistic Net Climate Benefit):** Propagating the joint posterior $p(\boldsymbol{\Theta} \mid D)$ to $H_{\mathrm{assess}} = 100\text{ yr}$, verify that the facility satisfies $P(\Delta \mathcal{C}_{100} > 0 \mid D) \ge 0.95$, $E[\Delta \mathcal{C}_{100} \mid D] \ge C_{\mathrm{target}}$, and $Q_{0.05}(\Delta \mathcal{C}_{100} \mid D) > 0$.

---

## 9. Experimental Pilot Design: Testing the Plastic-Pool, Ag-Waste, and Sand-Cap Protocol

To empirically falsify or validate this architecture before scaling to full mine pits, a 24-month, two-phase pilot is structured around a $1.0\text{ ha}$ ($10,000\text{ m}^2$) array of shallow plastic pools ($5 \times 0.2\text{ ha}$ HDPE-lined sub-basins, $h = 0.30\text{ m}$) paired with three controlled benthic deposition treatments inside a flooded pit (or high-pressure benthic pit-column simulators).

### 9.1 Experimental Treatments for Gate 5 (Testing the Sand Cap Hypothesis)

Using $^{13}\mathrm{C}$-bicarbonate labeling during Stage 2 cultivation to tag the autotrophic algal carbon ($^{13}\mathrm{C}_{\mathrm{algae}}$) distinctly from both background pit carbon and agricultural waste carbon, equal pulses of concentrated bottom sludge ($1,000\text{ kg C}$ per pulse, at $25\text{ g DW L}^{-1}$) are injected into three benthic treatments:

1. **Treatment A (Uncapped Surface/Shallow Control):** Algal sludge deposited at shallow, oxygenated depth without sand capping—measuring maximum aerobic remineralization rate ($k_{\mathrm{aerobic}}$).
2. **Treatment B (Deep Anoxic Pit Floor — Uncapped):** Algal sludge injected to the deep anoxic pit center ($\ge 150\text{ m}$) without sand capping—measuring baseline anaerobic degradation, upward diffusive $DIC/DOC$ flux, porewater porosity ($\phi$), and unmitigated $\mathrm{CH_4}$ ebullition.
3. **Treatment C (Deep Anoxic Pit Floor — Periodic Sand Capping):** Algal sludge injected to the deep anoxic pit center followed by a $2\text{ cm}$ broadcast layer of iron-bearing coastal/crushed sand after each cycle—directly measuring Terzaghi porewater expulsion ($\Delta \phi$), reduction in upward $DIC/DOC$ flux, and AOM methane oxidation efficiency within the sand cap.

### 9.2 Year-1 and Phase-2 Pilot Budget (Low-Head Plastic Pool Configuration)

Because shallow HDPE-lined earth pools ($\Delta H \approx 1\text{ m}$) and gravity sludge flushing eliminate expensive high-pressure cross-country pipelines and mechanical centrifuges, upfront capital costs drop significantly compared to inland high-head designs:

| Work Package | Lean Pilot ($0.2\text{ ha}$) | Full Pilot ($1.0\text{ ha}$) | Primary Deliverable |
| :--- | :--- | :--- | :--- |
| **1. Gate 0 Pit and Permits** | AUD $0.35\text{ M}$ | AUD $0.60\text{ M}$ | Hydrogeology and EPA/DEM approvals |
| **2. Plastic Pools and 1m Pumps** | AUD $0.25\text{ M}$ | AUD $0.65\text{ M}$ | HDPE liners, sumps, $1\text{ m}$ axial pumps |
| **3. Ag-Waste Pre-Treatment** | AUD $0.15\text{ M}$ | AUD $0.30\text{ M}$ | Screening, pasteurization, $\mathrm{N:P}$ dosing |
| **4. Flocculation and Drop-Pipe** | AUD $0.15\text{ M}$ | AUD $0.35\text{ M}$ | Decant skimmers and central-pit diffuser |
| **5. Sand Spreader and Chambers** | AUD $0.20\text{ M}$ | AUD $0.45\text{ M}$ | Sand broadcaster and 3 benthic chambers |
| **6. Sensors, $^{13}\mathrm{C}$ and IFCB** | AUD $0.35\text{ M}$ | AUD $0.75\text{ M}$ | $\mathrm{CH_4/N_2O}$ analyzers, IRMS, IFCB |
| **7. Operations and Contingency** | AUD $0.55\text{ M}$ | AUD $1.40\text{ M}$ | 3–5 FTEs, logistics, $15\%$ contingency |
| **Total Funding Envelope** | AUD $2.00\text{ M}$ | AUD $4.50\text{ M}$ | Empirical closure of Gates 0–7 |

---

## 10. Conclusion

By relocating primary separation into shallow, plastic-lined coastal pools operating at $\approx 1\text{ m}$ pumping head, substituting agricultural waste for synthetic fertilizers, decanting $95\text{--}98\%$ of clarified seawater directly back to the ocean, and locking the concentrated algal sludge beneath periodic sand caps in the deep center of an adjacent mine pit, the revised SPAM-V framework resolves the fundamental hydraulic and thermodynamic bottlenecks of marine biomass CDR. While a single commercial-scale pit facility can sequester $60,000\text{ to }300,000\text{ tCO}_2\text{e yr}^{-1}$ ($13\text{ to }40\text{ MtCO}_2$ cumulative vault capacity), scaling this low-head architecture across $1,000$ coastal and near-coastal mine voids globally offers a falsifiable, instrumentally verifiable pathway to $0.06\text{--}0.31\text{ GtCO}_2\text{e yr}^{-1}$ of durable carbon removal.
