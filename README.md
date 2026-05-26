# Urban Drainage Evaluation & LID Modeling: Räcknitz (Dresden, Germany)

## Project Background
The urban drainage network in the Räcknitz zone of Dresden faces significant hydraulic stress during heavy rainfall events, leading to systemic localized flooding and pipe surcharging. To address these capacity deficits without relying solely on traditional, expensive gray infrastructure upgrades, this project focused on assessing the current network's weak points and evaluating the mitigating effects of green infrastructure.

The core engineering objective was to model the existing stormwater network, diagnose flooding locations, integrate Low Impact Development (LID) sustainable solutions, and conduct a comprehensive, long-term water balance analysis to verify if the optimized system could successfully manage peak runoff volumes.

## My Core Contributions & Role
As the urban drainage and hydrologic modeling specialist on this project, I executed the following technical workflows:
* **Hydraulic System Diagnosis:** Built and analyzed the existing urban drainage network to pinpoint exact nodes and conduits prone to surcharging and surface flooding during design storm events.
* **LID Infrastructure Design:** Conceptualized, sized, and configured Low Impact Development (LID) controls (such as rain gardens, bioretention cells, or permeable pavements) directly within the catchments to reduce peak surface runoff.
* **Scenario Comparison & Capacity Analysis:** Simulated and compared "Before LID" and "After LID" scenarios to evaluate how decentralized green infrastructure altered hydrograph peaks and brought the existing pipe network back within safe operating capacities.
* **Long-Term Water Balance Simulation:** Executed continuous, long-term simulations to evaluate the continuous water balance metrics, tracking total infiltration, evaporation, and storage changes within the catchment over time.
* **Catchment Parameterization:** Processed subcatchment characteristics, including terrain slope calculations and impervious surface percentages, directly for the hydrologic routing setup.

## Tools & Technologies Used
* **EPA-SWMM:** Developed the primary hydrologic and hydraulic engine for network routing, subcatchment parameterization, LID configuration, and continuous water balance tracking.
* **MS Excel:** Processed rainfall time-series data and conducted system-wide mass balance error calculations.

## Project Structure
* `/models` : Contains the EPA-SWMM network files (`.inp`) for both the baseline and LID-optimized scenarios.
* `/results_plots` : Exported runoff hydrographs, node flood volumes, and long-term water balance charts.
