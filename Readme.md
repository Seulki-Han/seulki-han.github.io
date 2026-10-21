# Seulki Han, Ph.D.

**Postdoctoral Researcher**  
Department of Chemical & Biomolecular Engineering  
University of Delaware

<div style="display: flex; flex-wrap: wrap; gap: 24px; align-items: center;">
  <a href="mailto:seulkih@udel.edu">Email</a>
  <a href="CV_Seulki_Han.pdf">CV</a>
  <a href="https://scholar.google.com/citations?hl=en&user=onHXfuEAAAAJ&view_op=list_works&sortby=pubdate">Google Scholar</a>
  <a href="https://www.linkedin.com/in/seulkihan">LinkedIn</a>
</div>

## Adaptive Learning and Optimization for Process and Infrastructure Decisions

**How should technologies, processes, and infrastructure be designed and transitioned together under changing and uncertain conditions?**

I develop models and optimization methods to connect technology performance with process design and infrastructure planning. My work combines physics-informed learning, process simulation, and mathematical optimization to study how engineering decisions at different scales affect one another.

I am a postdoctoral researcher working with Professor Marianthi G. Ierapetritou at the University of Delaware. I received my Ph.D. in Chemical and Biomolecular Engineering from the University of Connecticut in 2025, advised by Professor George M. Bollas. I earned my M.S. and B.S. in Energy and Chemical Engineering from Incheon National University, where I worked with Professor Jiyong Kim.

## Research Vision

My goal is to connect technology development, process design, and infrastructure planning through **adaptive decision systems**. I am developing a research program that uses engineering decisions to guide learning, preserves the process information needed for system-level design, and revises transition plans as new evidence emerges. Three connected questions guide this work.

- **What should we learn before scaling up?**  
  Use commercial design decisions to identify which uncertain scale-up relationships matter and prioritize measurements that help distinguish competing designs.

- **What process information do infrastructure decisions need?**  
  Preserve the process relationships needed for reliable system decisions and translate system needs into quantitative targets for process improvement.

- **When should a transition plan change?**  
  Update planning models as new information becomes available and determine when the benefits of revising a pathway outweigh the cost of changing course.

These questions form **a feedback loop**. Experimental and operating data improve process models, which inform infrastructure decisions. System-level decisions then guide further learning, process development, and plan revision.

Initial applications will focus on **sustainable fuels, circular resource systems, and low-carbon infrastructure**.

<img src="fig1_research_vision.svg" alt="Research vision showing feedback between technology learning, process design, and infrastructure planning" width="100%">

## Selected Research

### Physics-Informed Learning for Evolving Systems

Tool wear develops over time, but sensor measurements do not directly capture the wear state. Data-driven models can also lose accuracy when operating conditions change. During my Ph.D., I developed a physics-informed recursive symbolic regression framework that uses each wear prediction as the next state input, together with sensor measurements and operating variables, to build explicit, interpretable equations.

Across 14 milling cases with different cutting conditions and workpiece materials, the model achieved an **average test R² of 0.93** and compared favorably with published tool wear models. The framework also supports remaining useful life prediction.

<img src="fig2_physics_informed_learning.svg" alt="Physics-informed recursive symbolic regression framework and tool wear prediction results" width="100%">

**Related Publication**

- **Han, S.**, Awasthi, U., and Bollas, G. M. (2025). [Physics-informed symbolic regression for tool wear and remaining useful life predictions in manufacturing](https://doi.org/10.1016/j.jmsy.2025.03.023). *Journal of Manufacturing Systems*, 80, 734–748.


### Integrated Process Design and Optimization

Process performance depends not only on individual technologies but also on how they are integrated. I use process modeling, surrogate modeling, and optimization to examine how technology selection and process configuration affect cost, energy use, and resource recovery.

For industrial carbon utilization, I developed a superstructure optimization framework for converting coke oven gas into hydrogen, methanol, Fischer–Tropsch fuels, and methane. The optimal process configuration depended on the objective. A single separation step minimized cost and energy use, while maximizing hydrogen production required additional reforming, shift, and separation steps.

In my current work on converting food waste to volatile fatty acids (VFAs), I developed surrogate models for fermentation and recovery and optimized both stages together. Across the studied feedstock compositions, joint optimization reduced total annual cost by **22–45% compared with optimizing each stage separately**, while maintaining or improving overall VFA yield.

<img src="fig3_VFA.svg" alt="Joint optimization of food waste fermentation and VFA recovery, including cost comparisons" width="90%">

**Related Publications**

- **Han, S.** and Ierapetritou, M. A surrogate-driven optimization framework for volatile fatty acid (VFA) production and recovery from food waste. *Bioresource Technology* (under review).
- **Han, S.**, Kim, S., Kim, Y. T., Kwak, G., and Kim, J. (2019). [Optimization-based assessment framework for carbon utilization strategies: Energy production from coke oven gas](https://doi.org/10.1016/j.enconman.2019.03.007). *Energy Conversion and Management*, 187, 1–14.


### Energy Infrastructure Design and Planning

Energy infrastructure planning involves decisions about technology selection, facility location, capacity, transportation, and investment timing. I developed a multi-period optimization model for national renewable energy planning in Korea. The results showed how transportation costs influence network design. Electricity and liquid fuels were produced centrally in the region with the most abundant resources, while hydrogen production was distributed across regions closer to demand.

My current work extends this approach to U.S. sustainable aviation fuel (SAF), integrating seasonal corn availability, existing ethanol plants, storage, rail and pipeline networks, and airport demand. As SAF demand increases, the optimal network shifts from centralized production to a more distributed system that uses existing facilities across multiple regions. Seasonal feedstock availability shapes production and transportation decisions, while feedstock procurement and SAF upgrading account for most of the total system cost.

<img src="fig4_SAF.svg" alt="U.S. sustainable aviation fuel supply chain design and infrastructure planning results" width="100%">

**Related Publications**

- **Han, S.** and Ierapetritou, M. A national-scale optimization framework for sustainable aviation fuel deployment. *Computers & Chemical Engineering* (under review).
- **Han, S.** and Kim, J. (2019). [A multi-period MILP model for the investment and design planning of a national-level complex renewable energy supply system](https://doi.org/10.1016/j.renene.2019.04.017). *Renewable Energy*, 141, 736–750.

## Publications

### Journal Articles

1. Shapiro, A. J., O’Halloran, R. C., Tavares, D., Huynh, D., **Han, S.**, Shi, R., Gupta, Y., O’Dea, R., Haney, S., Otsuka, Y., Sadula, S., Vlachos, D. G., Ierapetritou, M., Levia, D. F., and Epps, T. H. (2026). [Forest residue harvest optimization: Spanning the bridge between plant biology and biorefinery performance](https://doi.org/10.1039/D6GC01047D). *Green Chemistry*, 28, 12662–12676.

2. **Han, S.**, Awasthi, U., and Bollas, G. M. (2025). [Physics-informed symbolic regression for tool wear and remaining useful life predictions in manufacturing](https://doi.org/10.1016/j.jmsy.2025.03.023). *Journal of Manufacturing Systems*, 80, 734–748.

3. **Han, S.**, Yang, Q., Pattipati, K. R., and Bollas, G. M. (2022). [Sensor selection and tool wear prediction with data-driven models for precision machining](https://doi.org/10.1002/amp2.10143). *Journal of Advanced Manufacturing and Processing*, 4(4).

4. **Han, S.**, Mannan, N., Stein, D. C., Pattipati, K. R., and Bollas, G. M. (2021). [Classification and regression models of audio and vibration signals for machine state monitoring in precision machining systems](https://doi.org/10.1016/j.jmsy.2021.08.004). *Journal of Manufacturing Systems*, 61, 45–53.

5. You, C.<sup>†</sup>, **Han, S.<sup>†</sup>**, and Kim, J. (2021). [Integrative design of the optimal biorefinery and bioethanol supply chain under the water-energy-food-land (WEFL) nexus framework](https://doi.org/10.1016/j.energy.2021.120574). *Energy*, 228, 120574. (<sup>†</sup>Equal contribution)

6. **Han, S.** and Kim, J. (2019). [A multi-period MILP model for the investment and design planning of a national-level complex renewable energy supply system](https://doi.org/10.1016/j.renene.2019.04.017). *Renewable Energy*, 141, 736–750.

7. **Han, S.**, Kim, S., Kim, Y. T., Kwak, G., and Kim, J. (2019). [Optimization-based assessment framework for carbon utilization strategies: Energy production from coke oven gas](https://doi.org/10.1016/j.enconman.2019.03.007). *Energy Conversion and Management*, 187, 1–14.

8. **Han, S.** and Kim, J. (2017). [Optimization-based integration and analysis of a complex renewable energy system for the transportation sector](https://doi.org/10.1016/j.cherd.2017.09.029). *Chemical Engineering Research and Design*, 128, 1–14.

9. **Han, S.** and Kim, J. (2017). [An optimization model to design and analysis of renewable energy supply strategies for residential sector](https://doi.org/10.1016/j.renene.2017.05.030). *Renewable Energy*, 112, 222–234.

10. **Han, S.**, Won, W., and Kim, J. (2017). [Scenario-based approach for design and comparative analysis of conventional and renewable energy systems](https://doi.org/10.1016/j.energy.2017.04.063). *Energy*, 129, 86–100.

## Contact

**Seulki Han, Ph.D.**  
Department of Chemical & Biomolecular Engineering  
University of Delaware

Email: [seulkih@udel.edu](mailto:seulkih@udel.edu)
