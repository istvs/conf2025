---
description: ISTVS 2025 | October 6-9, 2025 | Lebanon, New Hampshire, USA
---

# Abstracts

### 0051 - GROUND VEHICLE DETECTION METRICS AND TERRAMECHANICAL CHARACTERIZATION DERIVED FROM A DISTRIBUTED ACOUSTIC SENSING SYSTEM DEPLOYED ON AN ARCTIC ICE ROAD

**Authors:** _Aaron Meyer, Adrian Doran, Abhishek Bhagat, Meghan Quinn, Keith Wilson, Matthew Kimball, Jennifer Picucci, Wei Huang, Russ Alger_

**Key Topics:** Detection & tracking Terramechanics Distributed fiber-optic sensing Distributed acoustic sensing

**Abstract:**

We present results from vehicle testing conducted on an Arctic ice road in February 2025 and monitored with a fiber optic distributed acoustic sensing (DAS) system. The DAS sensing element, a 1-km telecommunications-grade fiber-optic cable, was deployed in three configurations: surface-laid on snow, surface-laid on ice, and frozen into ice. We utilized an amplitude-only DAS system that recorded strain-rate time series with a channel spacing of 5 m. Detection metrics as a function of deployment configuration were derived against multiple vehicles transiting at variable speeds. Detection statistics are shown to vary with deployment conditions and target characteristics, suggesting that sensor performance can be optimized by accounting for environment and source type. Additionally, we used the fiber-optic sensor and vehicle excitations to interrogate the propagation medium. We present evidence that observed differences in frequency-dependent transmission loss can discriminate DAS cables embedded in ice and snow. This work resulted from an international collaboration enabled by the International Cooperative Engagement Program for Polar Research (ICE-PPR).

***

### 0270 - PERFORMANCE ASSESSMENT OF AN OFF-ROAD VEHICLE ACROSS DIFFERENT TERRAINS

**Authors:** _Luca Zerbato, Carl M. Becker, Andries J. Peenze, Enrico Galvagno, P. Schalk Els_

**Key Topics:** Off-road performance Experimental testing Tyre-terrain interaction

**Abstract:**

The prediction of vehicle performance during off-road missions has historically been a complex task due to the interaction between tyres and soft soil. A comprehensive characterisation of vehicle performance across different terrains is essential for a full understanding of tractive and handling behaviour. Moreover, it is crucial to discuss the tools and methods needed to extract relevant information from off-road testing, as standardisation in this area is lacking compared to on-road testing. This paper focuses on characterising vehicle performance using experimental data collected during an off-road testing campaign conducted across various terrains, including Kalahari Desert sand and gravel pavements. For longitudinal dynamics, coast-down, acceleration, braking, and Drawbar Pull tests are performed to assess rolling resistance, traction, and braking capabilities under off-road conditions. For lateral dynamics, constant-radius tests are conducted on gravel terrain to evaluate cornering behaviour. The synthesis of test analysis results serves as the foundation for developing simplified lumped-parameter handling models and estimating contact parameters for tyre–terrain interaction models.

***

### 0280 - REAL-TIME GROUND SEGMENTATION AND TERRAIN TOPOGRAPHY MAPPING USING POINT CLOUDS

**Authors:** _Jyotirmoy Mukherjee, Giri M Kumar, Andrea L'afflitto, Hannah White, Corina Sandu_

**Key Topics:** Off-road navigation terrain segmentation point cloud processing real-time mapping

**Abstract:**

The abstraction of the world in a virtual space known as a map is crucial to enable motion planning. Autonomous mobility over uneven terrains requires the model of terrain topography to account for surface profile induced factors that affect the feasibility of planned trajectories. Point cloud-based environment modeling has been particularly effective due to their ability to produce depth information. However, when deployed in UGVs, they encapsulate both traversable terrain and positive obstacles which must then be distinguished. This work introduces a novel and fast point cloud segmentation algorithm called the inverse ray tracing algorithm to classify traversable and non-traversable points.

The segmented point cloud is then collated together to create a comprehensive map. To this end, we present a Bayesian method using inverse sensor models that generate a 3D voxel grid of the terrain’s topography and a second method using convex hulls around classified terrain points, sequentially appending points to generate the terrain topography map. The proposed results are suitable for UGVs operating in GNSS-denied environments. Our approach integrates sensor fusion from a visual-inertial sensor, wheel encoders, and an inertial measurement unit with an extended Kalman filter to maintain precise odometry. The effectiveness of the proposed algorithms has been experimentally validated on a Terramechanics rig and compared with point cloud obtained from a 3D scanner, which resulted in a chamfer distance of approximately 1 mm, demonstrating high accuracy. Additionally, the navigation stack has been deployed on the Clearpath Husky platform to generate real-time terrain topography and obstacle maps, proving the practical applicability and robustness of our proposed algorithms.

***

### 0375 - A GENERAL MODEL TO APPROXIMATE THE SLIPPAGE CURVE FOR APPLICATIONS FROM ANALYSIS OF THE TIRE AND SOIL CONTRIBUTIONS TO LONGITUDINAL SLIPPAGE

**Authors:** _Vladimir Vantsevich, Jesse Paldan, Jordan Whitson, David Gorsich, Lee Moradi_

**Key Topics:** Off-road mobility Soil characterization Tires

**Abstract:**

The traction-longitudinal slippage curve characterizes the interaction of a driving wheel and deformable terrain and has important considerations affecting the performance of the wheel and of the vehicle. Knowledge of the slippage is crucial to off-road vehicle mobility and energy efficiency assessment and wheel control applications. To be able to analyze and compare the efficiency of different tires on the same terrain, or a tire on different terrains, the tire slippage should be split into two components to determine contributions of the tire and soil to the tire traction characteristic. A new exponential formulation of the longitudinal slippage was previously derived for this application. Many analytically-inspired-empirical based math models exist to describe slippage curves, which are validated, recommended, and being used in software products to approximate tire-terrain performance. To use these models in research with split tire and soil contributions would require rigorous research effort on re-deriving equations for each model because each is based on different mathematical theory and statistical constraints; such effort may not lead to a positive result. As an alternative approach, the analytical split traction-slippage curve is proposed as a general model to approximate other formulations of the slippage curve which can then be split into separate tire and soil slippage curves. Computational simulations of other slippage models are performed and their resulting curves are fit to the new exponential function to analyze the effectiveness of the split slippage model to approximate other models of traction-slippage curves and soil characterization. Using the split traction model, equations are derived to quantify tire and soil contributions the slip power losses.

***

### 0397 - MODELING, DESIGN, AND ASSEMBLY OF SPRING TIRES

**Author:** _Michael LU_

**Key Topics:** Spring Tires Terramechanics Drawbar Pull Testing Robotics Lunar Rovers

**Abstract:**

With a renewed interest in the Moon and the need for autonomous lunar rovers that drive longer distances and operate over extended durations, designing efficient and robust mobility systems is paramount. Created by NASA Glenn Research Center, the spring tire is a compliant airless tire engineered for planetary rover missions in lunar and Martian environments. It consists of hundreds of coiled springs woven together to create a toroidal-shaped mesh wheel that can deform to uneven terrain, providing additional durability and traction. This work aims to apply this technology to two robotic testbeds: ERNEST, an autonomous lunar traversal rover built at NASA Jet Propulsion Laboratory, and IPEx, a lunar regolith mining robot built at Kennedy Space Center. This thesis discusses the modeling of these spring tires with numerical methods along with the design of two spring tire prototypes for use on the aforementioned rover platforms. A streamlined assembly process for these compliant wheels is also outlined as well as the results of compression testing, rough terrain driving, and drawbar pull testing to assess their performance.

***

### 0398 - CONTACT DYNAMICS SLOPE STABILITY

**Authors:** _Tomas Berglund, Joakim Rydman, Martin Servin_

**Key Topics:** realtime simulation slope stability analysis mobile earthmoving equipment

**Abstract:**

A heavy vehicle operating near a steep slope alters the stress distribution and might cause the slope to collapse. The result can be catastrophic for the operator, the machine, and for other units in the area. Computational methods for assessing the risk for slope collapse has existed for a long time in geotechnics but are limited to static conditions without mobile equipment.

We explore a contact dynamics approach to slope failure analysis. The method searches a space of potential failure surfaces for the most critical one. The soil in each potential failure surface is treated as a rigid body supported by contact forces with the interfacing (static) terrain. The body is subject to gravity and contact forces from any multibody systems, such as a vehicle, interacting with it. A Signorini-Mohr-Coulomb contact model is assumed, stating that the relative normal and tangential velocity should be zero along the interface unless the normal and tangential forces reach their limit conditions, that depends on the (internal) friction and cohesion parameters, in which case the body is prone to acceleration. The discretized equations of motion, constrained by the contact model, form a linear complementarity problem that is solved numerically. The solution reveals whether the configuration is unstable or stable, and is factor-of-safety (FOS). A search algorithm for finding the most critical failure surface, in terms of smallest FOS or highest acceleration, is developed and analysed. The method was implemented in the realtime physics engine AGX Dynamics. The tests shows that it gives reliable results, comparable with conventional LEM methods, and is computational efficient enough for being used with a realtime simulator of terrain vehicles.

***

### 0583 - DYNAMIC OFF-ROAD ROUTE PLANNING: INTEGRATING TERRAIN PASSABILITY AND WEATHER FOR OPTIMAL MOBILITY

**Authors:** _Wojciech Dawid, Krzysztof Pokonieczny, Marek Wyszyński_

**Key Topics:** terrain passability weather conditions off-road mobility route planning vehicle mobility modelling

**Abstract:**

The need to move vehicles off-road arises primarily in military operations and crisis management, where standard road networks may be insufficient or inaccessible. While vehicles typically follow existing roads, critical situations often require off-road movement to execute surprise maneuvers or reach remote locations beyond the infrastructure network. In such scenarios, effective planning is crucial and requires detailed geographical data to assess terrain conditions and vehicle mobility. To support this process, terrain passability maps are essential. These specialized maps synthesize geospatial data, classifying terrain based on how different types of vehicles can navigate it. Despite advancements in vehicle traction technology, such as improved suspension, tires, and tracks, many vehicles still struggle on muddy or waterlogged soils. The war in Ukraine underscored this issue, with reports of modern Russian tanks failing to traverse swampy, clay-rich terrain. This research presents advanced methods for dynamically determining off-road routes with varying difficulty levels while accounting for changing weather conditions. The proposed solutions not only enable real-time route adjustments based on current weather patterns but also incorporate meteorological forecasts, allowing for more strategic long-term route planning. The route determination process relies on the creation of dynamic terrain passability maps, which serve as a foundation for generating a graph that calculates optimal paths. These maps take into account the impact of precipitation on soil properties. By integrating this data, routes can be precisely adapted to both environmental conditions and terrain characteristics, significantly improving efficiency and safety in difficult operational areas.

***

### 0938 - AI-BASED TERRAIN PASSABILITY MODELING

**Authors:** _Marek Wyszyński, Krzysztof Pokonieczny, Wojciech Dawid_

**Key Topics:** terrain passability artificial Neural Networks (ANNs) off-road mobility geospatial Data vehicle mobility modelling

**Abstract:**

Terrain passability assessment is a crucial aspect of military operations, influencing strategic mobility and tactical decision-making. Traditional methods of evaluating terrain traversability rely on static maps and expert judgment, often lacking the precision needed for dynamic environments. This paper presents an AI-driven approach to terrain passability modeling using artificial neural networks (ANNs). In research two models ann\_full and ann\_fast— were developed to predict passability coefficients based on geospatial and hydrological data. The ann\_full model utilizes a comprehensive dataset of terrain attributes, while the ann\_fast model focuses on the most influential parameters to enhance computational efficiency. The models were trained and validated using military geospatial databases, including VMAP Level 2, applied to the Suwałki Gap region. Results indicate that the ANN-based models outperform conventional methods by providing a more granular and accurate assessment of terrain conditions. Comparative analysis of different modeling techniques, including statistical threshold methods and vegetation roughness factor (VRF) models, further underscores the advantages of machine learning approaches in terrain analysis. The proposed AI-driven methodology enhances decision support systems, providing real-time, data-driven insights for military and autonomous vehicle applications.

***

### 0954 - ENHANCING COMBINED SLIP MANOEUVRES IN HIGH CENTRE-OF-MASS OFF-ROAD VEHICLES USING A SEMI-ACTIVE SUSPENSION SYSTEM

**Authors:** _Christos Kapareliotis, Schalk Els, Andries Peenze_

**Key Topics:** Semi-Active Suspension Rough road Combined Slip braking in turn High centre-of-mass vehicle

**Abstract:**

Emergency driving scenarios require combined slip, where tyres generate longitudinal and lateral forces to slow the vehicle while following a path. Stability systems e.g. as ABS brakes and Electronic Stability Control assist in regaining control after loss of stability. These systems do not actively prevent instability. ABS and ESC systems do not have direct rollover prevention which is necessary in vehicles with a high centre of mass. For off-road vehicles, this challenge is exaggerated by uneven terrain, loose soil, and rollover risk. Stability control systems struggle with unpredictable road inputs, often compromising handling. A preventative system is needed that manipulates load transfer to improve tyre contact before traction limits are exceeded and where the roll angle of the vehicle can be directly controlled. This study proposes using a semi-active suspension system to improve performance during combined slip manoeuvres. By adjusting suspension parameters, the system manipulates load transfer, and enhances overall traction limits, reducing instability and rollover risk while maintaining steering and braking. A vehicle, equipped with a controllable semi-active suspension system is used as a test platform. A high-fidelity model is used for design and optimization studies. Results are validated using experimental tests, with open-loop manoeuvres using brake and steering robots for repeatability and controlled assessment. Preliminary findings indicate that a semi-active suspension system enhances combined slip performance, reducing instability risks. While this research begins on paved surfaces, it provides a critical foundation for off-road applications, where terrain variability further challenges the vehicle’s stability.

***

### 1056 - OPTIMIZING VEHICLE NAVIGATION OVER TERRAIN

**Authors:** _Anthony Farkas, Henry Hodges, Cooper Madrazo_

**Key Topics:** Optimal Travel Path Routing Mobility Prediction Fast running model Modeling and simulation Terramechanics

**Abstract:**

This abstract summarizes the theoretical approach and method of application used to identify available travel paths, based on the near real time assessment of the interaction between the vehicle and the deformable terrain surface. The framework of this system is based on two avenues of effort that are combined to provide high fidelity mobility corridors that the manned or unmanned vehicle can use to help ensure successful mission completion. The first avenue uses multiple layers of terrain data to determine parameters of map grid elements, including but not limited to: soil type, elevation, soil moisture, roughness, slope, and land cover. These layers are used to establish conditions the vehicle may encounter. The second avenue of effort is a 3DMDB physics-based, deformable soils vehicle model. A large array of operational conditions, are provided to the high fidelity model to produce a predicted mobility and operating speed for each. The resultant information is used to create a fast running model, which is then combined with the first avenue. By combining both avenues, the area of operation can be evaluated to determine the available terrain and the speed at which a vehicle can maneuver through a selected area. The fast running model is continuously updated with available vehicle parameters and sensor data, to assess the capability of the vehicle to continue through the operational area. The real time interaction of the vehicle with the terrain is assessed using established terramechanics, physics-based relationships, updating the prediction for the available routes, and speed which can be achieved. Using a cost based optimization model, a route based on the selectable criteria such as fastest or most efficient is then computed resulting in a recommended path.

***

### 1171 - EFFECT OF STRESS DISTRIBUTION MODEL IN WHEEL TRAVELING ANALYSIS USING THE EXTENDED TERRAMECHANICS MODEL

**Authors:** _Mai Shimizu, Shingo Ozaki_

**Key Topics:** Terramechanics Simulation Ground deformation Trafficability Stress evaluation

**Abstract:**

The development and operation of exploration rovers is essential for human lunar exploration, which is considered an international space exploration goal. However, the lunar surface is a completely different environment from that on the Earth because it is covered with regolith. Hence, it is difficult to evaluate rover’s traveling performance in advance. Under these circumstances, the extended terramechanics (xTerramechanics) model has been proposed that takes terrain surface deformation into account. Meanwhile, in a wheel traveling analysis, stress evaluation models are important in the evaluation of wheel-ground interactions such as forces, torques, and soil movements. In addition to the well-known parabolic stress evaluation model proposed by Wong and Reece, Tsubaki and Ishigami have proposed a Gaussian stress evaluation model based on direct measurement of stress distributions. This model may be able to suppress excessive shear stress behind the wheel and predict more realistic traveling performance even in assuming regolith surface. Therefore, this study systematically examined the effects of these stress distribution models by conducting a traveling analysis using xTerramechanics model. The results show that for small-diameter wheels, the Gaussian distribution model can predict practical traction performance with fewer parameters.

***

### 1424 - COHESIVE EFFECT BASED PEFORMANCE EVALUATION OF SINGLE-WHEEL DEM SIMULATION

**Authors:** _Gentaro Suda, Keisuke Takehana, Kazuya Yoshida_

**Key Topics:** Discrete element method Single-wheel test Lunar regolith Cohesion

**Abstract:**

In recent years, discrete element method (DEM) simulations have been increasingly developed to accurately evaluate wheel locomotion performance as an alternative and complement to experimental methods. Our previous research focused on two key aspects: the development and validation of DEM simulations accurately replicating single-wheel test outcomes, and comparative experiments between terrestrial sand and regolith simulant to investigate how differences in mechanical properties of sand affect wheel performance. Building upon this earlier work, the present study specifically addresses the cohesive properties characteristic of lunar regolith. Cohesion significantly influences the compaction of granular materials, potentially altering the traction performance of wheels operating on such terrain. In this paper, we systematically varied the cohesive component in particle-to-particle interactions within the DEM simulations to analyze the resultant traction performance in single-wheel tests. Results indicate that increasing particle cohesion markedly enhances traction forces. Furthermore, analysis of the relationship between slip ratio and traction performance revealed that higher cohesion notably moderates the rate of traction force change as slip ratio increases. This finding highlights that cohesive effects are particularly pronounced under low-slip conditions, suggesting cohesion plays a critical role in early stages of wheel-terrain interaction.

***

### 1536 - AUTOMATED SYSTEM FOR DETERMINING MILITARY ROAD AND TERRAIN PASSABILITY BASED ON TERRAIN, METEOROLOGICAL AND HYDROLOGICAL CONDITIONS

**Authors:** _Krzysztof Pokonieczny, Marek Wyszyński, Wojciech Dawid_

**Key Topics:** terrain passability weather conditions off-road mobility index of passability

**Abstract:**

The article will present a system that allows automation of the process of performing terrain passability analysis. The use of automation allows this analysis to be performed quickly and in any area of interest. As part of the research, methodologies have been developed for determining the index of passability (IOP), the task of which is to calculate measurable conditions of vehicle passability in a specific area, taking into account a variety of factors. The main task of these methodologies is to integrate data from various sources (mainly geospatial data: digital maps, meteorological and soil data) and determine an easy-to-interpret coefficient that will additionally take into account the traction characteristics of military vehicles. The determined coefficients will allow the generation of easy-to-interpret passability maps. Combining such a large amount of data from different sources made the resulting maps change their content over time as the meteorological situation changes. The terramechanics experiments carried out, made it possible to take into account the ability of specific vehicles used by the armed forces to travel on roads and roadless areas under specific meteorological and hydrological conditions. Taking into account the specifics of the weather data, the system generates passability maps both taking into account the current situation and also allows for the prediction of passability conditions. In this way, an “on-call, automatically updating passability map” was created, this allows the system to provide the commander with information on the ability to move troops not only for the present moment, but also, taking into account the forecasts. This gives an entirely new capability for planning the movement of troops over roads and roadless areas.

***

### 1868 - MODELING AND SIMULATION OF AUTONOMOUS VEHICULAR SYSTEMS AT ERDC - III VERIFICATION AND VALIDATION OF M\&S FOR AUTONOMOUS VEHICLES

**Authors:** _Peilin Song, Burhman Gates, Joshua Fairley_

**Key Topics:** Modeling and simulation (M\&S) verification and validation (V\&V) edge case raining fogging

**Abstract:**

Modeling and simulation (M\&S) of autonomous vehicles (AVs) for military applications requires rigorous verification and validation (V\&V) processes to ensure the reliability and safety of these systems in complex, dynamic environments. Only properly verified and validated, the Software Integrated Laboratory (SIL) can be used effectively in broader operational scenarios. Once a model that is properly verified and validated in normal cases can be extended to edge cases such as raining, fogging, and dusty conditions. This paper presents an overview of the V\&V efforts of SIL at the U.S. Army Engineer Research and Development Center (ERDC) to simulate autonomous vehicles. As the SIL is hierarchical in nature, we developed a corresponding hierarchical methodology for the V\&V of the SIL across different mission types. This methodology ensures that V\&V is performed at the component level before being elevated to the system level, providing a structured approach to ensure the accuracy and reliability of the simulations. The case study presented in this paper demonstrates the effectiveness and usefulness of the V\&V process developed by ERDC in validating autonomous vehicle systems. The paper discusses the frameworks and processes used to verify and validate these systems, highlighting the challenges and insights gained from applying V\&V practices to autonomous vehicle development.

***

### 1960 - EFFICIENT MODELLING OF THE EFFECT OF TIRE DEFORMATION DURING CONTACT WITH OBSTACLES

**Authors:** _Mahdi Maleki, Jozsef Kovecses_

**Key Topics:** Obstacle negotiation Reduced model deformable tires

**Abstract:**

The ability of compliant tires to deform plays a crucial role in enhancing their obstacle negotiation capability compared to rigid wheels. This work presents an efficient method for evaluating the effect of tire deformation by adjusting the contact parameters of a rigid wheel model. Instead of explicitly solving for structural deformations, the approach incorporates constraint kinetic energy at the moment of contact to account for deformation effects, ensuring computational efficiency while maintaining accuracy.

The method dynamically modifies contact parameters, such as normal vectors and contact points, to reflect the altered interaction between the tire and the obstacle. This adjustment enables the introduction of a reduced model that efficiently incorporates the effects of tire deformation without explicitly modelling structural flexibility, providing a computationally efficient yet accurate approach to analyzing obstacle negotiation.

The simulation results demonstrate that the proposed approach effectively replicates key deformation-induced behaviours observed in high-fidelity models while achieving real-time performance. This makes it a practical and efficient solution for vehicle dynamics studies, robotics, and autonomous vehicle applications where both computational efficiency and physical accuracy are essential.

***

### 2154 - SIMULATION OF DYNAMIC BEHAVIOR IN ARMORED VEHICLES USING MODIFIED OFF-ROAD VEHICLES FOR CIVIL PROTECTION APPLICATIONS

**Authors:** _Jorge Lopera, Juan Pablo Angulo_

**Key Topics:** Armored Vehicles Vehicle Dynamics Off-road vehicles

**Abstract:**

In the realm of civil protection at countries with security concerns like Colombia, armored vehicles play a crucial role in ensuring the safety and security of persons. These vehicles undergo significant modifications, including increased mass to enhance their armor features, which in turn alters their dynamic behavior. This study explores the feasibility of using an off-road vehicle to simulate the dynamic behavior of an armored vehicle, thereby providing a cost-effective platform for the development, and testing of non-sprung components. The project utilized a modified off-road vehicle with an initial mass of 2,500 kg. By incrementally adding ballast, the vehicle's mass was increased to 3,500 kg, simulating the weight of an armored vehicle. Dynamic tests were conducted on three types of terrains (gravel, mud, and asphalt), to evaluate the vehicle's performance under different conditions. Key parameters such as suspension travel, damping characteristics, and ride comfort were measured and analyzed. Preliminary results indicate that the modified off-road vehicle successfully replicates the dynamic behavior of an armored vehicle with a reliable degree of accuracy. Components, like the shock absorber increases their load and could harmful the vehicle dynamics for this type of vehicles. With this methodology it could be possible to analyze too the energy absorption and ride comfort metrics for these types of vehicles. This research demonstrates the potential of using older off-road vehicles as a viable platform for simulating the dynamic behavior of armored vehicles. The findings provide valuable insights for the development of non-sprung components, ultimately contributing to the enhancement of armored vehicle performance in civil protection applications.

***

### 2264 - MOBILITY TESTING ON FROST SUSCEPTIBLE SOILS AT FIELD CAPACITY

**Authors:** _Michael Parker, Clifford Witte, Allan Wheeler, Susan Frankenstein_

**Key Topics:** Mobility vehicle Arctic freeze/thaw field capacity organic soils

**Abstract:**

Frost susceptible soils include a wide variety of soil types from highly organic to fine grained silty soils. These soils can pose significant mobility challenges during each of the four seasons especially during the freeze/thaw transition periods between seasons. These mobility challenges have been on display during several conflicts throughout history with the most recent being the war in Ukraine. Maintaining mobility superiority during conflict is critical to avoiding immobilization and becoming a target while maintaining mobility in the Arctic can have similar consequences because immobilization can mean the difference between life or death due to the harsh environmental conditions. This research studies the effects on vehicle mobility across three vehicle classes including both wheeled and tracked platforms operating on peat and silty soils at field capacity. Testing occurred on unfrozen, partially frozen, fully frozen, and partially thawed soil conditions to capture the maximum tractive force during these transitional seasons and better predict cross-country vehicle mobility.

***

### 2448 - PRACTICAL RECOMMENDATIONS FOR IMPROVED TRAFFICABILITY USING A MATTING SYSTEM

**Authors:** _Bradley Hansen, Collin Davenport, Zachary Aspin, Brent Towne, John Rushing_

**Key Topics:** Terrain surfacing matting site stability mobility

**Abstract:**

Matting systems are heavily used by the US Army – Engineer Research and Development Center to increase offroad trafficability. However, practical recommendations for how much a matting system will improve trafficability based on vehicle type and soil conditions remains elusive. This effort uses three different vehicle weight classes with one matting system to quantify the trafficability improvement. In addition, this effort attempts to identify which soil testing equipment’s output best correlates with overall predictive performance of number of passes with and without matting. The soil testing equipment used are cone penetrometer, dynamic cone penetrometer, vane shear, clegg hammer, and light weight deflectometer. The outcome of this paper should yield how much the matting system improves with each vehicle weight class as well as which soil tester was the best predictor of performance.

***

### 2458 - OBTAINING FIRST ORDER TYRE PARAMETERS WITH INSITU TESTING

**Authors:** _Carl M. Becker, P. Schalk Els_

**Key Topics:** Tyre parameters friction coefficient in-situ testing laboratory testing surface roughness

**Abstract:**

In any vehicle dynamics simulation model, the tyre model is of upmost importance as it is the only component in contact with the terrain. In many cases engineers under estimate the contribution the tyre model makes to the reliability and accuracy of the simulation results. On larger off-road vehicles this is the case due to the limited tyre data and models available to the engineers as parameterize tyres are not trivial and can be very expensive compare to the cost of the tyre. On very large tyres the infrastructure required to conduct tyre parameterization tests are not available. Vehicles used on soft terrain are also often used on hard terrain. Tyre parameters are measured on hard terrain as the tyre carcass construction, inflation pressure and vertical load on the tyre dictates the linear section of the longitudinal and lateral tyre parameters. The maximum longitudinal and lateral load generated by the tyre is dictated by the surface roughness of the terrain over which the tyre transverse. In this study we conduct in-situ test on 2 vehicles on a specific surface. These results are compared to laboratory tests conducted on the same tyres and same surface. This method enables engineers to obtain first order tyre parameters to validate simulation models with limited and non-specialized equipment.

***

### 2469 - TERRA-V TOOLCHAIN: VIRTUAL VALIDATION AND OPTIMIZATION OF AUTONOMOUS VEHICLES IN UNPAVED TERRAIN

**Authors:** _Gerhard Skoff, Daniel Hassler, Gernot Hasenbichler_

**Key Topics:** Autonomous Systems Validation Offroad-Mobility Simulation

**Abstract:**

To ensure safe and robust autonomous offroad-operation, specific challenges must be managed, including robust terrain-specific obstacle detection. Virtual approaches have the potential to significantly shorten development time and effort. Adequate methods need to consider changing environmental conditions, as e.g. changes of the vegetation during the seasons of the year as well as weather. To manage all those requirements, a modular simulation platform has been developed.

The toolchain consists of six independent and flexible modules, which are all linked together to conduct simulations seamlessly and with best correlation to real world:

1. Vehicle-specific multibody dynamic simulation module of the vehicle, which can be derived from different multibody dynamic simulation tools, whereby a mathematical soft-soil model applies,
2. A terrain model, which utilizes a comprehensive set of specifically designed terrain elements, and which undergo AI-supported modifications, e.g. darkness, fog or rain during the validation process,
3. A sensor module, which can operate with different kinds of active and non-emitting sensors. Sensor selection and arrangement on the vehicle are optimized in the virtual sensor lab,
4. An autonomous algorithm, which is the system-under-test (SuT) and which gets optimized and validated,
5. Set of terrain-specific KPI’s, which define application-specific boundaries and qualification criteria,
6. A terrain-specific scenario database, where ontology-based automated offroad-scenarios are generated.

The sensor model and SuT get integrated into the Vehicle model, and the vehicle is executing the automatically generated, ontology-based testcase-combinations. Application-specific KPI’s are calculated and compared with target values.

***

### 2824 - LOCAL PATH PLANNING ON ROUGH TERRAIN FOR UNMANNED GROUND VEHICLE BY REINFORCEMENT LEARNING CONSIDERING SEARCH REWARD

**Authors:** _Ryosuke Eto, Fushiki Taguchi, Junya Yamakawa_

**Key Topics:** local path planning autonomous unmanned ground vehicle reinforcement learning rough terrain

**Abstract:**

Autonomous unmanned ground vehicles are expected to be utilized at disaster sites. The previously obtained map information for the site is often unreliable because disaster areas can change rapidly and unpredictably. Therefore, the vehicles must be able to recognize the surrounding rough terrain environment in real time and plan optimal routes to approach the destination safely. However, local path planning may fall into the local minimum solution and get stuck. Therefore, in this study, a method of avoiding a standstill by utilizing information entropy and route history to encourage exploratory behavior was investigated. In the proposed method, routes are selected by determining the vehicle behavior using reinforcement learning. For observation information, a Digital Elevation Model, an information entropy map of elevation, and a map that records the number of times the vehicle has traveled on the grid, in addition to the vehicle's state were used. The aim is to acquire the behavior of going to the target with selecting a safe route to avoid getting stuck by rewarding the vehicle for going to the target, avoiding uneven terrain, reducing information entropy, and not repeatedly driving in the same place. In this study, we tested the proposed method on each terrain with a single large obstacle and a dead-end by simulations. The simulation results showed that the vehicle can reach the target efficiently by introducing rewards for exploratory behavior.

***

### 2908 - DRAWBAR PULL EXPERIMENT AND ANALYSIS OF GROUSERED-TRACK UNIT ON SANDY TERRAIN

**Authors:** _Ryota Azuma, Tatsuya Maeda, Kosuke Horie, Shinichiro Miyai, Shunsuke Sugimura, Genya Ishigami_

**Key Topics:** Grousered-track unit Drawbar pull coefficient Slip ratio Sandy terrain

**Abstract:**

Tracked vehicles are commonly used on construction sites because of their high vehicle stability and traversability with large ground contact area. Grousers attached to the track shoe enhances vehicle stability and traversability, mitigating the risk of slipping on rough terrain. While many past studies investigated the mechanical effect of a single grouser shoe, experimental test of an entire grousered-track unit remain limited due to non-uniform the stress distribution of the track unit on the ground. In this study, we developed an experimental apparatus with a grousered-track unit and conducted drawbar pull experiment on sandy terrain. We measured the slip ratio and sinkage of the track unit with various traction load corresponding to the drawbar pull of the track unit. The relationship between the drawbar pull coefficient, which is the ratio of the drawbar pull to the vertical load of the track, and the slip ratio was examined. The experiments confirmed that the slip ratio remains constant when the drawbar pull coefficient is approximately 0.4 or lower. Within this range, the track unit maintains small sinkage and a stable driving state. However, when the drawbar pull coefficient exceeds approximately 0.45, the slip ratio sharply increases as larger traction load cases the track unit to an unstable driving state by repeating the move-and-stop motion. This trend was observed regardless of the varied vertical load. These findings suggest that the relationship of the slip-drawbar pull coefficient and the threshold for stable/unstable driving state are useful for evaluating the traversability of the grousered-track unit.

***

### 3332 - CALIBRATION AND SENSITIVITY ANALYSIS OF DEM MODELS USING TRIAXIAL TEST OF 6 LUNAR REGOLITH SIMULANTS.

**Author:** _Isabel Casasbuenas_

**Key Topics:** Discrete element method Triaxial test Soil Characterization High-fidelity simulation

**Abstract:**

Understanding the geotechnical properties of lunar soils is essential for predicting their mechanical behavior under varying stress conditions, which is critical for future surface operations such as mobility, construction, mining, and foundation design. However, due to the Moon's reduced gravity, the mechanical behavior of regolith may differ significantly from that observed under Earth conditions. To address this challenge, this study uses Discrete Element Method (DEM) simulations to analyze and calibrate the behavior of lunar regolith simulants under terrestrial gravity to enable more realistic modeling under lunar conditions. Triaxial compression tests were performed on six lunar regolith simulants to determine shear strength parameters, including cohesion, internal friction angle, and stiffness. These laboratory results served as calibration targets for DEM simulations in EDEM software. DEM models were iteratively adjusted to match experimentally the stress-strain responses obtained, accounting for particle size distribution and shape characteristics. A subsequent sensitivity analysis was conducted to identify micromechanical parameters' influence on model accuracy, particle friction, rolling resistance, and contact stiffness. The outcomes provide a validated calibration framework and highlight which parameters are most critical for replicating realistic regolith behavior. This work contributes to developing high-fidelity DEM models for lunar soil and supports their integration into rover mobility studies and surface engineering applications.

***

### 3375 - REAL-TIME SIMULATION OF FLEXIBLE TRACKS FOR ACCURATE VEHICLE-TERRAIN INTERACTION

**Authors:** _Mahdi Maleki, Wing Hang HO, Joe Hewlett, Marek Teichmann, Jozsef Kovecses_

**Key Topics:** Tracked vehicles Flexible tracks Real-time performance

**Abstract:**

Modelling flexible tracks is essential for accurately simulating the mobility of tracked vehicles, particularly in off-road environments. Traditional high-fidelity models provide detailed insights but are computationally expensive, making them unsuitable for real-time applications. This work presents an efficient approach for simulating flexible tracks by dynamically calculating track shape, tension, and contact forces while maintaining computational efficiency.

The track shape is determined based on an ordinary differential equation (ODE) that relates wheel positions, track tension, wheel sinkage, and pressure distribution. Ray casting is used to estimate sinkage along the track, while track forces (including normal, shear, and lateral forces) are computed using established pressure-sinkage and shear stress-displacement relationships. The model updates track shape each time step by estimating entrance and exit angles at wheel contact points and fitting a polynomial to ensure smooth transitions. Contact forces are then distributed to the wheels, enabling accurate simulation of traction and mobility.

This approach efficiently captures key deformation behaviours observed in high-fidelity models while achieving real-time performance by incorporating track tension effects and interaction forces without explicitly solving complex structural deformations. The method is well-suited for vehicle dynamics studies, robotics, and autonomous systems where fast and reliable terrain interaction modelling is required.

***

### 3559 - MODELING LIGHT DETECTION AND RANGING (LIDAR) RESPONSE IN SNOWY ENVIRONMENTS

**Authors:** _Brian Brady, Aaron Meyer, Sergey Vecherin, Mike Parker_

**Key Topics:** LiDAR snow simulation autonomous vehicle

**Abstract:**

The sensors used by a robust, off-road autonomous vehicle must be capable of detecting obstacles in any weather conditions, but this becomes especially important during inclement weather with reduced visibility. Snowfall is no exception to this and poses extremely challenging conditions to vehicles exclusively employing Light Detection and Ranging (LiDAR) systems for object detection. Snowflakes may occlude “hard” targets in the vehicle’s path of travel or introduce noise from “soft” detections of the snowflakes themselves. This study highlights preliminary results from a simulation that reproduces these effects within the U.S. Army Corps of Engineers’ Virtual Autonomous Navigation Environment (VANE). The simulation accurately models snowflake size, concentration, and velocity while accounting for sensor-specific modes of operation. VANE simulations provide vehicle designers with a rapid and affordable method to evaluate LiDAR perception and autonomy response in snowy conditions.

***

### 3985 - KODIAK ROBOTICS - AI DRIVER FOR MILITARY APPLICATIONS

**Author:** _Bobby Bonello_

**Key Topics:** Autonomy AI ML

**Abstract:**

Kodiak Robotics develops a scalable, adaptable autonomy system for commercial and defense applications. Its modular, hardware-agnostic autonomy stack seamlessly integrates across vehicle platforms, reducing costs and enabling continuous upgrades without major overhauls. Built around a redundant, safety-critical architecture, Kodiak’s system leverages machine learning, sensor fusion, and waypoint navigation for real-time decision-making in dynamic environments. A key differentiator is its modular sensor pod design, consolidating cameras, LiDAR, and radars into a single, easily replaceable unit, ensuring high uptime and simplified maintenance in austere conditions. Kodiak prioritizes real-world deployment to refine its technology. A prime example is its partnership with Atlas Energy Solutions in the Permian Basin, where fully autonomous trucks transport freight in demanding conditions. These deployments validate Kodiak’s reliability, efficiency, and cost-effectiveness, serving as a critical bridge to defense applications. For military use, Kodiak’s autonomy system enhances force protection and operational resilience by reducing human exposure in high-risk environments. Its autonomous ground vehicles ensure mission-critical supplies reach the front lines safely. Its modular, vehicle-agnostic design supports the DoD’s open architecture initiatives, promoting interoperability and reducing vendor lock-in. Kodiak’s approach accelerates defense modernization by adapting proven commercial autonomy for military needs. With a focus on safety, redundancy, and adaptability, Kodiak Robotics delivers next-generation logistics and mobility solutions, enhancing operational efficiency and reducing risk in commercial and contested environments.

***

### 4050 - AUTONOMOUS MOBILITY IN DRY TERRAINS: FIELD AND MODELING EXPERIMENTS, AND MULTIPLE SENSORS DATA FUSION

**Authors:** _Jose L Hernandez, Brent W. Towne, Gentry Berry, Laura Walizer_

**Key Topics:** Autonomous mobility Dry off-road terrain Low-visibility conditions Dust dispersion New instruments and data analysis

**Abstract:**

Autonomous mobility of ground vehicle in low-visibility conditions, such as dusty off-road terrain, requires robust object detection capabilities for accurate navigation. This work presents a novel approach to support autonomous mobility in dry terrains by modeling and integrating multi-sensor data to create a 3D representation of dust dispersion. Modeling dust plumes at small scales (<100m) and short periods (<1min) must accurately represent realistic dispersion; however, that is challenging using computational fluid dynamics (CFD) methods which require validation to determine model confidence limits. The goal of the dust experiments and modeling are to provide accurate dust simulations for virtual environments. This work describes experimental tests using a small truck driving under different dry terrain and environmental conditions. The experiments were conducted prior full development of a CFD model tool configured to represent dust dispersion at the mentioned scales. Results confirm a good correlation among optical (LIDAR and cameras) and direct sensors. Dust emission rates at different soil surfaces, used in the CFD model, were estimated using a portable wind tunnel. A set of novel dust and ambient monitoring units along with reference methods to test accuracy of novel sensors, were used in the experiments. At higher truck speed, the LIDAR’s returned laser intensity decreases due to higher dust concentrations lifted by the truck. Cameras observing the physical domain in three orthogonal directions provide views to build an optical proxy of 3D dust concentration based on monitoring data. The first version and developments of the CFD modeling tool will be discussed.

***

### 4122 - DEM ANALYSIS OF EFFECT OF INTERPARTICLE FORCES ON SAND-OUTFLOW BEHAVIOR FROM HOPPER UNDER LOW-GRAVITY ENVIRONMENT

**Authors:** _Shunsuke Muryokoji, Shingo Ozaki_

**Key Topics:** Microgravity Discrete Element Method (DEM) Van der Waals Force Electrostatic Force Hourglass

**Abstract:**

Understanding the behavior of granular materials under various low-gravity conditions is essential for planetary exploration, as it impacts lander interactions, rover mobility, and in-situ resource utilization processes. However, ground-based experiments using parabolic flights and drop tower facilities are limited by short-duration microgravity conditions, making it challenging to fully capture behavior of granular materials. To address this, numerical simulations provide a powerful alternative. This study employs the discrete element method (DEM) to simulate sand-outflow behavior from hoppers under reduced gravity, based on the Hourglass experiment conducted aboard the International Space Station (ISS). The experiment utilized artificial gravity (0.06G–2G) to observe the deposition and flow characteristics of different granular materials. Using the DEM, we modeled silica sand samples (#5 and #8), incorporating contact forces, rolling resistance, and van der Waals forces/electrostatic forces to evaluate their impact on particle motion. The results show that silica sand #5 exhibited minimal adhesion effects, whereas silica sand #8 demonstrated significant accumulation of sand on walls, particularly under lower gravity conditions. Moreover, neither van der Waals nor electrostatic forces alone could fully replicate experimental results, indicating that both must be considered for accurate modeling. These findings emphasize the importance of interparticle forces in regolith behavior under low gravity and provide insights into granular material interactions in extraterrestrial environments. This study could contribute to the design and optimization of robotic systems for planetary exploration, particularly in excavation, mobility, and construction applications.

***

### 4135 - RIDE QUALITY MBD SIMULATION SENSITIVITY STUDY

**Authors:** _Reid Pulley, Gary Bailey_

**Key Topics:** 3D Terrain MBD Simulation Tire model Sensitivity Analysis Ride Quality

**Abstract:**

The goal of this effort is to conduct a vehicle response (ride quality) sensitivity analysis varying two parameters:

1. 3D terrain resolution, and 2) MBD tire model fidelity. Technologies such as LiDAR and photogrammetry have made it possible to collect high resolution 3-D surface elevation data. In this context “high resolution” terrain is considered to be a dataset with grid spacing of 1 inch or smaller. Legacy profile data typically has a sample spacing of 3 inches. According to Nyquist theory, the sample rate limits the frequency content of a signal. Thus high resolution terrain data will increase the frequency input range to a vehicle. However this high frequency input may not be significant in terms of ride quality response.

3-Dimensional terrain is more representative of real world operating conditions than legacy ride quality courses, and creates a very different dynamic response than traditional 2D RMS courses. The forces generating this gross motion response are created by the tire/track interaction with the terrain. This paper focuses on the dynamic response of wheeled vehicles with pneumatic tires. The tire functions as a mechanical filter which limits the vibration input from the ground surface. Multiple tire models are available for use in the various 3D multibody dynamics simulation environments. This study utilized the Hexagon ADAMS simulation tools and considers the varying fidelity and computational cost of available tire models. The purpose of this effort is to characterize the expected ride quality response with respect to both terrain resolution and tire model fidelity in a simulation environment.

***

### 4217 - A COMPUTATIONALLY EFFICIENT PLUG-IN FOR HIGH-FIDELITY OFF-ROAD VEHICLE DYNAMICS STUDIES ON DEFORMABLE TERRAINS

**Authors:** _Amir Khosravian, Sadegh Yarmohammadisatri, Corina Sandu, Yinglong HE, Davide Tavernini_

**Key Topics:** Off-road mobility Vehicle dynamics Tire-terrain interaction Deformable terrain modeling Flexible tire modeling

**Abstract:**

Accurate simulation of off-road vehicle dynamics on deformable terrains remains computationally challenging despite advances in vehicle dynamics modeling. In this paper, we develop an efficient yet high-fidelity off-road simulation toolbox, which incorporates the Hybrid Soft Soil Tire Model (HSSTM), a semi-empirical, experimentally validated off-road tire model, and the widespread simulation platform IPG CarMaker. This integration enables high-fidelity simulations on deformable terrains and facilitates the development of off-road vehicle control algorithms for highly dynamic scenarios. The integrated tire-vehicle model provides a tool for simulating the ride, handling, and mobility of off-road vehicles. HSSTM models the tire as discretized lumped masses with Kelvin-Voigt elements on a 3D deformable terrain. Unlike rigid-ring models, HSSTM captures tire flexibility, which is crucial for simulating tire dynamics on medium-hard to rigid terrains. To enhance computational efficiency, we adopt a Dynamic Terrain Adaptation algorithm that models only a localized portion of the terrain around the vehicle, dynamically updating as the vehicle navigates. Simulations on non-deformable terrain demonstrate that HSSTM tire forces are in good agreement with existing on-road tire models (e.g., MF-Swift). Further, simulations on deformable terrains in longitudinal and lateral scenarios (including force coupling) confirm accurate off-road dynamics representation across various terrain types. The plug-in assesses contact patch pressure, normal and shear forces, elastic and plastic sinkage, and multi-pass effect. Finally, a sensitivity analysis across various simulations with different tire and terrain discretization levels evaluates the accuracy/efficiency trade-off of our plug-in.

***

### 4335 - EXTENDED BRUSH MODEL FOR USE WITH GRAVELLY TERRAIN

**Authors:** _Devon Cox, P. Schalk Els_

**Key Topics:** Extended brush tyre model Off road mobility Agricultural tyres Tyre soil interaction Model validation

**Abstract:**

This paper presents the development of a physics-based brush tyre model extended for applications beyond conventional smooth surfaces. The research addresses limitations in existing tyre models when simulating vehicle dynamics on non-smooth, hard terrain. A comprehensive literature survey informed the methodological approach, which combines a physics-based brush model with empirical tread and soil models implemented in MATLAB. Initial validation results demonstrate promising performance, indicating that the combination of empirical soil characterization with the physics-based brush model effectively predicts tyre forces on non-smooth terrain. The model provides a framework for predicting traction limits in off-road conditions, expanding the simulation capabilities for vehicle dynamics on complex surfaces.

***

### 4342 - CORNERING PERFORMANCE OF RIGID WHEEL IN GRANULAR MEDIA USING COARSE-SCALE DEM MODELS

**Authors:** _Aidan Dickerson, Bohumir Jelinek, George Mason, Thomas Skorupa, Michael Cole, Jody Priddy_

**Key Topics:** Off-Road Mobility Tractive Performance Discrete Element Method Rigid Wheel Side Slip

**Abstract:**

Understanding interactions of wheels and tracks with granular media under variable loading conditions, including longitudinal and side slip, is critical for prediction of mobility for wheeled and tracked vehicles in off-road environments. The discrete element method (DEM) is routinely used for modeling interaction of soil with track and tires, but the method’s accuracy needs to be better established. In this work, two DEM models from the Generic EDEM Material Model (GEMM) database from Altair®'s EDEM™ software package, which were identified (Jelinek et el. 2025) as the best match to physical experiments, are used to calculate tractive performance of a rigid wheel in sand under braked, towed, and powered conditions with side slip. The simulations follow the experiments by Shinone et al., 2010, examining a 165/60R13 wheel with constant circumferential velocity of 97.6 mm/s and vertical contact load of 980 N operating in powered conditions under forward slips in the range of -5.9% to 54.8%. The steady-state tractive forces on the wheel in sand were evaluated under the same forward slip conditions as in the experiment, except with added side slip of 3, 6, and 12 degrees. The side-slip effects on net traction, gross traction, and sinkage of the wheel in sand are evaluated by comparison with forward-slip-only results. Lateral forces and overturning moments were then calculated and compared with relevant relationships derived from physical measurement and other simulation methods. The results indicate a good match to experimental trends, encouraging further use and calibration of the DEM soil-wheel interaction models.

***

### 4368 - IMPROVING THE EXPANDING/CONTRACTING SPEED OF A PUSH-ROLLING ROVER ON LOOSE SURFACES WITH STEEP SLOPES

**Authors:** _Daisuke Fujiwara, Hiroto Fujisawa, Tasuku Hoshino, Kojiro Iizuka_

**Key Topics:** Mobile robot Push-rolling motion Loose soil Planetary explorations

**Abstract:**

The wheeled rover has played an important role in planetary or lunar exploration. The planet and moon surfaces are covered with granular materials, which causes the wheeled rover to get stuck. To suppress wheel slippage, the rover, which utilizes shear force beneath the anchored wheel, can effectively climb a loose surface with steep slopes. Previous studies have developed various types of push-rolling and wheel-walking rovers. Furthermore, our previous study developed a minimal configuration rover and confirmed that it can climb loose surfaces with steep slopes while suppressing slippage. During its movement, the rover changes its wheelbase length and moves its wheels using the resistance forces of the anchored wheels. However, the variable speed of the wheelbase length remains constant at 20 mm/s, and the effect of this speed on the rover’s traveling performance is still unclear. The traveling speed of the rover with small wheels tends to slow down; therefore, understanding the potential to improve its speed is important. The purpose of this paper is to validate the impact of the changing speed of the wheelbase length on the climbing ability. This paper presents a testbed rover that can change the speed of the expanding/contracting wheelbase length and performs the climbing experiment on loose soil with steep slopes. The experimental results suggested that driving performance was maintained even when the expanding/contracting speed increased three times faster than the conventional speed.

***

### 4395 - ANALYSIS AND STUDY OF LUNAR ROVER TRAVERSABILITY UNDER THE ENVIRONMENTAL CHARACTERISTICS OF THE LUNAR SOUTH POLE

**Authors:** _Haoran Xie, Yan Shen, Zhichen Jia, Ruizhe WU, Yuzhi Wang, Jiyin Xie, Meng Zou_

**Key Topics:** Lunar rover Traversability model Wheel-soil interaction model DEM-MBD coupled simulation Dynamic illumination map Ephemeris algorithm

**Abstract:**

Speed and energy consumption are critical factors in trajectory planning for lunar rovers in sun-synchronous orbits on the lunar surface. Both vehicle deceleration and excessive energy use may alter the rover's path, potentially disrupting the mission. This study focuses on China's lunar south pole exploration missions, analyzing mobile system energy consumption. It investigates the mechanical properties of polar regolith, slope distributions in landing zones, and dynamic illumination patterns, creating an evaluation framework combining terrain mechanics, illumination, and energy management. A traversability model for lunar rovers under low gravity was developed, integrating wheel-soil interaction, suspension-terrain compatibility, and illumination-energy synergy. DEM-MBD simulations showed that as slope increased from 0° to 20°, wheel slip ratio surged from 12% to 88.5%, and energy consumption rose from 1.18W to 7.39W. Simulations under constraints for water-ice craters (1m depth, 0.15 depth-to-diameter ratio) showed average slip ratios of 44.7% and peak pitch angles of 21.07°. Prototype testing validated the model, with errors within ±8%. Using NASA LRO-LOLA lunar terrain data and high-fidelity simulations, 2D velocity-energy maps identified traversable zones. A 3D dynamic illumination model, based on SPICE ephemeris algorithms and terrain occlusion relationships, was developed. These results provide technical solutions for China's Chang'e-7 mission.

***

### 4416 - PREDICTION OF SOIL RUT DEPTH AND TIRE TRACTION FORCES USING BEKKER AND DEM-FEM TECHNIQUES

**Authors:** _Mehari Tekeste, Pius Jjagwe, Thomas Way, Kumaran Periannan, Raghuram Thiagarajan, Mohamed Abdeldayem_

**Key Topics:** DEM soil model PM-tire FEM model Inflation pressure Single tire tester Soil rut depth Traction forces

**Abstract:**

The study focuses on simulating the mobility systems of vehicles on soft terrains, which necessitates the use of physics-based soil models, tire models, and their interactions. A significant challenge lies in obtaining soil model parameters for empirical traction equations and high-fidelity DEM-FEM techniques, mainly due to the variability in soil initial conditions, such as soil bulk density. The objective is to simulate soil behaviors and traction forces related to pull and motion resistance using reduced mathematical models and DEM-FEM techniques. Bekker’s soil and DEM contact soil model parameters were calibrated using soil mechanics testing data on cohesive-frictional artificial soil. Predicted soil rut depth and traction forces from the two modeling techniques were validated against soil bin data from single tire testing using a Yokohama Geolandar radial tire (235/75R15) under two vertical loads (4 kN and 6 kN) and two tire inflation pressures (179 kPa and 241 kPa), with the tire operating in towing mode on dense and loose initial conditions. DEM elasto-plastic soil model and FEM PM-tire model demonstrated better accuracy in predicting soil sinkage compared to the Bekker parameterized soil modeling technique. The Bekker approach provided relatively accurate traction force predictions for free-towing scenarios, particularly in denser soil conditions and with over-inflated tire pressure compared to correctly inflated conditions. The DEM-FEM modeling effectively captured soil behaviors, including compression and bulldozing, in a loose soil state. The comparison of Bekker’s reduced physics and high-fidelity DEM-FEM approaches for predicting soil-to-tire interactions offers opportunities to accelerate the automation of mobility systems on deformable terrains.

***

### 4417 - THE STATUS OF SOIL PHYSICAL, MECHANICAL, AND CHEMICAL PROPERTIES TWO YEARS AFTER DEFORESTATION IN A MILITARY TRAINING AREA

**Authors:** _Kersti Vennik, Tõnu Tõnutare_

**Key Topics:** Soil shear strength Cone index Trafficability Soil chemical elements

**Abstract:**

Military training areas are unique in their function and usage. These areas must endure intensive and repeated movement of wheeled and tracked military vehicles, as well as dismounted troops. Depending on the training requirements of defense forces, military training areas can undergo rapid land-use changes. For instance, when new firing ranges or maneuvering grounds are needed, forests may be cleared to create open areas. Deforestation has a significant impact on soil properties. Logging and uprooting activities displace soil layers and alter soil structure. The primary goal of training land managers is to restore the usability of deforested areas as quickly as possible, making the restoration of disturbed ground a key focus. The objective of this study was to assess the status of soil physical properties, chemical composition, and trafficability conditions two years after deforestation. As deforestation contributes to the release of carbon dioxide (CO₂) into the atmosphere, it plays a significant role in climate change. A key objective of this study was to evaluate changes in soil CO₂ levels following deforestation. Measurements were conducted in 2020 at a military training ground in northern Estonia. The study included bulk density and moisture content measurements, as well as the determination of California Bearing Ratio (CBR) and Cone Index (CI) values for both disturbed and undisturbed areas. The plant-available nutrient content (P, K, Mg, Ca) was determined using the ammonium acetate-lactate (AL) method. Soil carbon and nitrogen content were measured using the Dumas method. Measurement results are presented, highlighting the effects of disturbance and recovery on soil properties.

***

### 4425 - TRACTION-SINKAGE-SLIP CHARACTERISTIC OF WHEEL MOBILITY ON LOOSE TERRAIN

**Authors:** _Keisuke Takehana, Kazuya Yoshida_

**Key Topics:** Single-wheel test Traction performance Sinkage

**Abstract:**

Accurately assessing the traction performance and sinkage of wheeled robots on soft terrain across varying slip ratios is essential. Our previous studies indicated that sinkage significantly influences traction performance under varying conditions such as load and velocity. In this study, we experimentally and analytically investigated the correlation between two critical output parameters: sinkage and traction performance. Single-wheel experiments were conducted by systematically varying wheel velocity, slip ratio, and load (equivalent to wheel weight), to determine the effect of changing sinkage levels on traction performance. Results showed no notable correlation when traction performance was plotted solely against sinkage for all collected datasets without considering slip ratio. However, grouping data according to slip ratios revealed a distinct negative correlation, indicating traction performance declines with increased sinkage. Additionally, it was observed that the slope of this negative correlation varies according to the slip ratio. These detailed insights into traction performance, sinkage, and slip ratio dynamics enhance the understanding of wheel performance and will contribute to more accurate predictions and optimized designs in future robotic mobility systems.

***

### 4525 - SERRATED LEADING EDGES FOR SNOW PLOWS IN TACTICAL WINTER OPERATIONS

**Authors:** _Clifford Witte, Michael Parker_

**Key Topics:** Snow Plows Arctic Snow Ice Removal Traction Packed Snow Compacted Snow Vehicle Performance

**Abstract:**

To prevent excess wear and tear of paved roadways and increased maintenance of winter service vehicles, snowplows typically utilize a bolt on straight hardened metal blade affixed to the 'cutting', or leading edge of the plow. However, when compared to serrated blade leading edges, straight blades leave a compacted frozen surface left adhered to the road requiring further deicing by spreading of sand or road salt. For weather conditions or surfaces when wear of the blade or roadway is not the primary concern, such as in battlefield engineering, serrated plowing edges may be more effective at rapidly creating higher traction roadway surfaces than straight blades.\
Serrated blades are low cost to manufacture and take only minutes for plow operators to bolt on or remove In March 2025, researchers at the Cold Regions Research & Engineering Laboratory conducted performance testing of an instrumented light US Army tracked vehicle on two surfaces plowed separately with serrated and straight blades. Researchers conducted Drawbar Pull and rolling resistance tests on each surface to measure tractive power of the instrumented vehicle. The effects of using a serrated edge plow blade are seen to be similar to the combined effects of using a straight plow blade and a separate grooming vehicle. Traction increases seen from using serrated edge plow blades for snow and ice removal operations will be shown to be particularly advantageous in tactical domain environments such as plowing over dirt, frozen ground, ice layers, or older high density snow pack.

***

### 4558 - IN-SITU SOIL-PROPERTY ESTIMATION AND BAYESIAN MAPPING WITH A SIMULATED COMPACT TRACK LOADER

**Authors:** _W. Jacob Wagner, Ahmet Soylemezoglu, Katherine Driggs-campbell_

**Key Topics:** Autonomous Earthmoving Soil-Property Estimation Physics Infused Neural Networks Robotics Terrain Mapping

**Abstract:**

Existing earthmoving autonomy is largely confined to highly controlled and well-characterized environments due to the complexity of vehicle-terrain interaction dynamics and the partial observability of the terrain resulting from unknown and spatially varying soil conditions. To overcome these restrictions and facilitate development of more robust autonomous earthmoving, a soil-property mapping system is proposed to extend the environmental state.

A GPU accelerated elevation mapping system is extended to incorporate a blind mapping component which traces the movement of the blade through the terrain to displace and erode intersected soil, enabling separately tracking undisturbed and disturbed soil. Each interaction is approximated as a flat blade moving through a locally homogeneous soil, enabling modelling of cutting forces using the fundamental equation of earthmoving (FEE). Building upon our prior work on in situ soil-property estimation, a method is devised to extract approximate geometric parameters of the model given the uneven terrain, and an improved physics infused neural network (PINN) model is developed to predict soil properties and uncertainties of these estimates.

A simulation of a compact track loader (CTL) with a blade attachment is used to collect data to train the PINN model. Post-training, the model is leveraged online by the mapping system to track soil property estimates spatially as separate layers in the map, with updates being performed in a Bayesian manner. Initial experiments show that the system accurately highlights regions requiring higher relative interaction forces, indicating the promise of this approach in enabling soil-aware planning for autonomous terrain shaping.

***

### 4579 - ANALYSIS OF PASSENGER TIRE-SALTED PAVEMENT INTERACTION: A TRACTION PERSPECTIVE

**Authors:** _Erin Fenton, Zeinab El-sayegh_

**Key Topics:** Tire Mechanics Vehicle Dynamics Terramechanics Smoothed Particle Hydrodynamics Finite Element Analysis

**Abstract:**

This paper introduces a novel approach for investigating the interaction between a passenger car tire and salted pavement. A passenger car tire size 235/55 R19 was modelled within a Finite Element Analysis (FEA) software called Virtual Performance Solution (VPS) using 28 layers including solid, layered membrane, beam and shell elements. The modelled tire was validated in static and dynamic domains using manufacturer-provided data. The salt used to sit on top of the pavement was modelled using Smoothed-Particle Hydrodynamics (SPH) techniques and calibrated using shear-strength test. The salted pavement–tire interaction required the use of node-to-segment contact algorithm with edge treatment to ensure no penetration between the salt particles and the tire elements. The focus of this paper is to investigate the tractive efforts of the driven tire over the salted pavement under different operating conditions. The operating conditions include vertical loads of 3.5 kN, 5 kN, 8 kN and a nominal inflation pressure of 228 kPa at constant angular velocities equivalent to longitudinal speeds of 10 kph, 50 kph and 100 kph. To understand the impact salt has on the driving conditions of icy roads several tests including a 57 mm, 114 mm and 171 mm salt depth was selected to understand the impacts of the amount of salt on a surface. This study provides insight to the use of road salt in the winter months in Canada. As road salt is crucial in winter climates it is important to understand the implications that salting pavement will have on the performance of passenger car tires through advanced computational techniques. By understanding the implication salt has on different pavements affected by winter a deeper understanding of safety, and tire traction performance can be achieved.

***

### 4739 - MULTI-ROBOT AUTONOMOUS SOLUTIONS

**Authors:** _Forrest Johnson, Amanda Sgroi_

**Key Topics:** Vegetation Filtering Negatives enhanced blackout high speed convoy leader/follower collaborative robotics attritable

**Abstract:**

Since 2009, autonomy and robotics at Applied Research Associates, Inc. (ARA) have been designed from the ground up to handle the most rugged off-road environments with a high priority on reaching the destination target without fail. When it comes to autonomous systems, vehicle characteristics such as stability, wheelbase, perception mounting height, and traction approach (wheels vs. tracks) significantly impact autonomous performance, so ARA has installed & trained our autonomous systems on many popular defense tactical vehicles including the PLS, MRZR TD, MRZR-X, HMMWV, and Alpha series. This proven expertise uniquely positions us to deliver a reliable, low Size, Weight, and Power system (30lbs, 180W nominal) that meets the demands of USSOCOM’s internal transport requirements. In addition, ARA has participated in the GEARS program, demonstrating autonomous high-speed (30mph) leader/follower convoy scenarios ready for contested logistics applications. Our sophisticated perception system detects and avoids obstacles concealed behind vegetation.

New capabilities include our zero human intervention AI module, such as retro traverse maneuvers for obstacle avoidance, multi-point turn escape strategies for navigating tight spaces, and dynamic system software algorithm switching to apply the most effective approach to the immediate terrain.

We are also investing heavily in collaborative robotics and attritable systems which are a game changer in the battlespace. We have developed a tracked multi-purpose robotic platform suitable for high mobility arctic transport as a mothership for launching and managing large UGV/UAV robotic swarms on the frontlines. All of these systems are performing collaborative autonomous teaming through ARA’s Mission Planning Management System.

***

### 4755 - RELATIONSHIP BETWEEN SEASONAL VEHICLE PERFORMANCE AND TERRAIN PROPERTIES FOR PREPARED SOILS

**Authors:** _Susan Frankenstein, Allan Wheeler, Bruce Elder_

**Key Topics:** soil freeze/thaw peat rut depth

**Abstract:**

Laboratory and field studies were conducted over three years on fine grained and peat soils measuring the effects of soil properties on vehicle performance, namely drawbar pull, and motion resistance. Tests were conducted for unfrozen, frozen, and thawed states using eight different vehicles both wheeled and tracked. In the laboratory, soil moisture and temperature could be controlled. In both the field and laboratory, the soils were tilled then smoothed before testing. The soil was characterized pre and post testing using a variety of strength instruments. Rut depths associated with motion resistance tests were recorded. This paper discusses the effects of measured soil properties on rut depth as a function of soil state as well as compares results to existing algorithms. When possible, comparison of soil properties from different measurement techniques are compared.

***

### 4970 - L-BAND MICROWAVE RADIOMETRY FOR NON-CONTACT MOISTURE MEASUREMENT OF FIELD TRAFFICABILITY

**Authors:** _Maik Wolleben, Joseph Dvorak, Kaleb Dempsey, Michael Peterson_

**Key Topics:** Moisture Sand Trafficability Microwave Radiometry

**Abstract:**

The moisture content of soil is the single most important source of uncertainty for the trafficability of fields. Because of increasing frequency and intensity of rain events, planting or field equipment operations are more likely to occur as soon as possible after a rain events. For harvesting, pest control, planting or other field operations timeliness is critical for the effectiveness of the work and ultimately the yield produced. The trafficability necessary to complete field work is largely a factor of soil moisture from the surface down to 15 to 30 cm; however, large temporal and spatial variations complicate sensing and deploying machinery in the areas that are sufficiently dry to support fieldwork.

This work focuses on high sand content soils: sandy loam, loamy sand and sand. Under controlled conditions L-band Microwave Radiometry was used to measure the moisture content in a non-contact configuration. Initial testing focused on the effect of interference from cellular, emergency and other radio sources of radio frequency interference. A second test was conducted in proximity to general aviation operations. Initial concerns regarding noise from most sources was found to be less of a problem than anticipated.

However, at the frequency employed (1.4 GHz), a poor correlation with time domain reflectometry at 3 cm depth was observed, suggesting that the sensing depth of the microwave sensor is deeper than the TDR probe. Higher microwave frequencies may need to be employed to match the critical depth for sandy soils, A number of alternative applications exist for these moisture sensors which may be of value in other applications or surfaces with higher clay content or higher salinity.

***

### 5493 - EFFECTS OF ELECTRONIC CONTROL SYSTEMS ON AUTONOMOUS VEHICLE PERFORMANCE IN GRANULAR TERRAIN

**Authors:** _Bohumir Jelinek, Aidan Dickerson, Angela Card, Greg Henley, George Mason, John Ethan Salmon, Ch. Michael Gibson, Tyler Hannis, Tom Skorupa, Michael Cole, Jody Priddy, Miriam Figueroa-santos, Sara Boyle, Jeremy Mange_

**Key Topics:** Off-Road Mobility Soft Terrain Electronic Stability Control Antilock Braking System Double Lane Change

**Abstract:**

Understanding effects of electronic control systems, such as Antilock Braking System (ABS) and Electronic Stability Control (ESC), and their interaction with the steering control algorithm is critical for improving mobility and maneuverability of autonomous wheeled vehicles in off-road environments. In this work, we evaluate effects of wheel-speed based ABS and yaw-rate-following ESC on the performance of autonomously driven Polaris RZR vehicle performing a double-lane-change (DLC) maneuver in granular terrain by identification of maximum DLC passing speeds. Two lateral speed controllers are compared: simple PID and Stanley autonomous steering controller, along with the longitudinal speed controller that accelerates the vehicle to identify maximum DLC passing speed. The simulations were conducted using Chrono simulation package with the Soil Contact Model (SCM) parameters. The SCM parameters were calibrated to represent dry sand by using data from published experimental measurements. The ABS effects were found to be negligible or detrimental, while ESC augmented the lateral steering control algorithm allowing the vehicle to achieve higher DLC passing speeds.

***

### 5658 - WINTER ROUTE PLANNING ALGORITHM

**Author:** _Mark Bodie_

**Key Topics:** Route planning Graph Mobility

**Abstract:**

Cold regions represent an especially challenging environment for maneuver. In addition to standard obstacles which occur in less extreme environments, the surface itself can become an obstacle. Winter surfaces are characterized by low strength, resulting in deep vehicle sinkage with high motion resistances. In this work, we developed a cold regions route planning (WRP) algorithm that identifies low risk routes that minimizes the energy required by the vehicle to complete a mission. The algorithm fuses weather, terrain, and vehicle information to generate a unique on and off-road graph of the area of interest. A winter surface algorithm is used to predict the current snowpack’s depth and density using weather and terrain information. This information along with vehicle data, is used to generate the vehicle’s motion resistance and work associated with surface compaction, tree push over force, and gravity forces. Search requests are initiated, and optimal routes are displayed through kml files, enabling the use of existing GIS software to interface with the WRP algorithm. Experiments were conducted at the Camp Ethan Allen Test Site to validate the algorithm. Driven and predicted routes and mission completion times were compared with favorable results. Additional algorithm enhancements are identified to improve route accuracy and in-field operation.

***

### 5740 - EFFECTS OF REMOTE SENSING FOR GROUND VEHICLE PATH PLANNING

**Authors:** _Burhman Gates, Phillip Price_

**Key Topics:** routing remote sensing trafficability mobility

**Abstract:**

This paper explores the utility of drone-based remote sensing to driving and routing for ground based vehicles. Drones can provide additional information about the terrain and trafficability to path planning algorithms, however using this remote sensing actor can incur additional costs. Quantifying the value of this remote sensing actor in terms of distance and time traveling can allow these risks to be appropriately weighed and acted on. Notional terrains are traversed with different sensing ranges and accuracies.

***

### 6001 - MODELING AND SIMULATION OF AUTONOMOUS VEHICULAR SYSTEMS AT ERDC - II SOFT SOIL MODEL SUPPORT IN VEHICLE DYNAMICS

**Authors:** _Peilin Song, Burhman Gates, Joshua Fairley_

**Key Topics:** Vehicle-Terrain Interaction Traction Sinkage ProjectGL

**Abstract:**

In vehicular system development, ensuring the fidelity of vehicle dynamics models is critical, especially for military vehicles operating primarily on off-road terrains, where mobility is significantly influenced by various types of soft soils. The U.S. Army Engineer Research and Development Center (ERDC) has been a pioneer in off-road mobility research, conducting extensive testing on various vehicles across different terrains. These tests have led to the development of empirical formulations for traction, resistance, and sinkage of tractive elements, such as tires and tracks.

ERDC/GSL's Vehicle-Terrain Interaction (VTI) API, which covers both wheeled and tracked vehicles, provides a comprehensive set of empirical relationships that simplify the modeling of vehicle-terrain interactions. These relationships streamline the modeling process, simplify the overall vehicle models, and significantly enhance simulation fidelity. This paper discusses the integration of the VTI API as a plugin within Unreal Engine and ProjectGL, aiming to improve the accuracy and realism of vehicle mobility simulations. By incorporating VTI into these platforms, we achieve high-fidelity simulations of vehicle performance on soft soils, thereby advancing the modeling and analysis of military vehicle mobility in off-road conditions.

***

### 6010 - VALIDATION OF MECHANISTIC DEM CALIBRATION

**Author:** _Zamir Syed_

**Key Topics:** DEM calibration soil modeling granular dynamics

**Abstract:**

A mechanistic method of calibrating DEM parameters to mechanical responses of soil and dense granular matter is presented. DEM calibration literature was explored in detail and the evidence for systematic DEM calibration was tabulated. The resulting method was validated using physical test data in the existing literature.

***

### 6198 - VEHICLE IMPACT ANALYSIS USING REMOTE DATASETS

**Authors:** _Heidi Howard, Jaime Miranda Ramirez, Israel Lopez Toledo_

**Key Topics:** terrain impact vehicle impact model soil models

**Abstract:**

The Army currently has limited capabilities to calculate training impacts for multi-day-vehicle exercises. The ARNG has deployed a program of record for eXportable Combat Training Capability (XCTC) which utilizes a tracking system similar to those used for fleet management. The use of spatial and temporal data from these training events can then be linked to vehicle severity models developed by CERL, CRREL, and other agencies to quantify actual impacts to ground, air, and water. CERL is utilizing data from historic exercises to develop a machine learning capability that could then project out impacts to the terrain from existing and future vehicle platforms. This presentation will discuss lessons learned and accuracy of the model estimations for sinkage and disturbance.

***

### 6366 - SIMULATION-BASED OPTIMIZATION OF A TRACKED VEHICLE SUSPENSION SYSTEM

**Authors:** _Markus Pogulis, Martin Servin, Joel Nilsson_

**Key Topics:** Simulation-based optimization Multibody dynamics Tracked vehicle suspension Ride quality optimization Derivative-free optimization Surrogate modeling

**Abstract:**

This research considers simulation-based optimization of a tracked vehicle suspension system. We focus on maximizing ride quality across a large spectrum of operational conditions rather than specific terrain/speed combinations, using surface roughness to guide our exploration of diverse scenarios.

The vehicle suspension system features 14 torsion rods and dampers subject to optimization. Using multibody dynamics simulation, we evaluate ride quality over diverse terrains at varying speeds, computing whole-body acceleration and vibrational dose values (VDV).

We analyze and compare alternative ways of posing and solving the problem of finding a suspension configuration that is optimal for a desired spectrum of terrains. We consider derivative-free optimization methods, including Particle Swarm Optimization (PSO) and Bayesian Optimization, and compare these to first learning and pre-building a surrogate model, prior to optimization. This surrogate strategy relates local terrain characteristics to vehicle performance metrics, such as acceleration-constrained velocity limits.

Preliminary work with PSO demonstrated significant ride quality improvements, with VDV reductions of 20-60% compared to baseline configurations, but was limited to optimizing only torsion rods for specific terrain/speed combinations. Our current research extends this by simultaneously optimizing both suspension and damping parameters and implementing an aggregated approach that optimizes performance across multiple terrains and velocities in a single cycle.

This work demonstrates how simulation-based optimization techniques can significantly reduce whole-body vibrations in tracked vehicles, improving both operational capabilities and crew endurance in challenging environments.

***

### 6540 - KRC BEVAMETER DEVELOPMENT AND MOBILITY DATA COLLECTION

**Authors:** _Russell Alger, Peter Alger_

**Key Topics:** Bevameter Bekker-Wong Vehicle Mobility Traction Sinkage

**Abstract:**

The Keweenaw Research Center (KRC) at Michigan Tech University has designed and built an automated Bevameter to measure in-situ soil strength and derive Bekker-Wong mobility parameters. Testing has been performed in a number of soils including high organic soils (peat), silts, sands, gravels, and lunar regolith at various moisture contents. A data set containing derived strength parameters is being built and results that are non-proprietary and non-controlled are shared with permission on the KRC website.

KRC has also performed several vehicle mobility tests both in the field and in the lab on the KRC single wheel tire tester. A large amount of this collected data is also available on the website with permission. All testing includes cone penetrometer, nuclear density, moisture, and surface friction when possible.

This paper will be an overview of the Bevameter and the data collected to date, as well as an overview of other mobility testing that has been performed.

***

### 6650 - RELIABILITY OF GRAVITY OFFLOAD FOR LUNAR ROVER WHEEL PERFORMANCE

**Authors:** _James Hurrell, Keisuke Takehana, Kentaro Uno, Kazuya Yoshida_

**Key Topics:** Discrete element method Lunar rover Single wheel test Simulation Gravity offload

**Abstract:**

Purpose: The impact of gravity and use of gravity offload on rover tractive performance is evaluated and compared between Earth and lunar environments. Single-wheel experiments and discrete element method (DEM) simulations of a micro-rover wheel modelled on the Rashid-1 rover designed for the Emirates lunar mission are conducted. The wheel's interaction with Toyoura sand and FJS-1 lunar regolith simulant is studied. Consideration is made for why the use of gravity offloading has been prominent and other options that are available.

Methods: Slip conditions, traction coefficient and grouser pitch for single-wheel experiments are measured for a range of fixed slip values at the expected rover load of 24.5 N at a nominal 0.02 m/s, termed a low-speed regime. Single-wheel simulations have been previously verified by comparison with experimental results. Lunar simulations can predict lunar gravity performance.

Results: Wheel performance regarding traction coefficient and tractive efficiency under lunar gravity matches that under Earth gravity. Traction performance in tractive force and resistive torque is reduced by the ratio of Earth to lunar gravity, 1/6, for the same mass. Earth gravity results for 4.1 N are understood to over-predict the traction coefficient compared to lunar conditions. Using load matching of 24.5 N in lunar gravity reduces performance.

Conclusion: Gravity offloading is unsuitable. Depending on the aspect desired to study the influence of gravity on the rover, consideration should be made to use either Earth conditions, granular scaling laws, or a full-scale reduction of the rover. This may change with a transition to high-speed wheel motion.

***

### 6775 - MODELING AND SIMULATION OF AUTONOMOUS VEHICULAR SYSTEMS AT ERDC - I SOFTWARE INTEGRATION LABORATORY: DEVELOPMENT AND APPLICATIONS

**Authors:** _Peilin Song, Burhman Gates_

**Key Topics:** Modeling and Simulation Autonomous Drive terramechanics Vehicle Dynamics Software Integration Laboratory

**Abstract:**

Unmanned Ground Vehicles (UGVs) are becoming critical assets for the Army, offering enhanced capabilities for mission execution. However, the complexity of autonomous systems presents challenges that traditional analysis tools are ill-equipped to handle. To address this, ERDC has developed a Software Integration Laboratory (SIL) to support the modeling and simulation (M\&S) of UGVs in virtual environments. The SIL provides a digital testbed for performance prediction and risk mitigation across both typical and edge-case scenarios. As part of ongoing test and evaluation (T\&E) endeavors, ERDC’s SIL supports a wide range of activities that complement physical field trials. This includes the creation of high-fidelity virtual environments that integrate vehicle dynamics, terramechanics, terrain models, and sensor simulations. These environments enable realistic testing of autonomous navigation systems—such as the Robotic Technology Kit (RTK) and its variants—in off-road and contested conditions. This paper highlights the design and capabilities of ERDC’s SIL and its application to autonomous ground vehicle testing and development. It demonstrates how digital experimentation using the SIL supports the integration of autonomous systems into manned-unmanned teams and helps inform future mission planning. The paper also presents the application of the SIL in various projects, including both single autonomous vehicle operations and the coordinated motion of multiple vehicles in team-based scenarios.

***

### 6905 - INVESTIGATING DATA COLLECTION AND PROCESSING STRATEGIES FOR UAV-BASED TERRAIN MODELS IN VEHICLE DYNAMICS SIMULATION

**Authors:** _Herman Hamersma, Christian Van Aswegen, Glenn Guthrie, Schalk Els, Carl Becker_

**Key Topics:** terrain modelling road profiling off-road mobility

**Abstract:**

Accurate modelling of the interaction between a tyre and the terrain is essential for effective vehicle dynamics simulation, especially in challenging off-road conditions. A previous study outlined the development of three-dimensional terrain models using images captured by an unmanned aerial vehicle (UAV) and suggested several avenues for further investigation. This study addresses those recommendations, which include: (1) examining the impact of various image collection strategies, such as different image overlap ratios, varying flight path altitudes, and using both orthographic and oblique images, and (2) expanding the previous results to encompass a broader range of terrains, including a comparison of experimental measurements from a test vehicle with simulation results. Additionally, the interpolation technique used to regularise the point cloud data was found to significantly affect the terrain model. Images were collected across multiple test tracks at a proving ground for which baseline measurements from a traditional mechanical profilometer were available for direct comparison with the UAV-obtained data. The findings reveal that while constructing three-dimensional terrain models from UAV data is straightforward, several potential pitfalls must be carefully avoided, as they can significantly affect the accuracy of the results. The results provide a step-by-step guide to developing terrain models of various surfaces, from relatively smooth man-made roads (e.g., an ISO 8608:2016 Class-C road) to very rough natural terrain, opening various avenues for future mobility research in challenging terrains.

***

### 6965 - CORRELATION BETWEEN OPTICAL REFLECTANCE AND LOAD-BEARING CAPACITY OF SOILS

**Authors:** _György Pillinger, Peter Prof. Kiss_

**Key Topics:** Optical Reflectance Load-Bearing Capacity Soils Moisture content

**Abstract:**

An important factor in route planning for autonomous off-road vehicles is determining soil condition, particularly load-bearing capacity. Direct (in situ) measurement of this soil property is challenging, and its determination through remote sensing technologies is an emerging area of research. In laboratory tests using prepared soil samples, a strong correlation was observed between the soil surface reflectance in the visible range (400-700 nm) and the load-bearing capacity. A bevameter device was used to determine the load-bearing capacity of each sample at various moisture contents. Measurements were taken for eight different soil textures at different moisture levels, starting from the dry state and gradually increasing to full saturation. This approach allowed us to observe how changes in moisture content affect the load-bearing capacity of each soil texture. Reflectance measurements were then performed on these samples using a portable spectrophotometer. The optical reflectance data were compared with the load capacity measurements obtained from the bevameter. This process enabled the development of a predictive equation that incorporates constants representing the soil's reflectance in its dry state. The resulting equation accurately captures the relationship between reflectance and load-bearing capacity under laboratory conditions. While these results are based on a controlled environment, they offer a valuable foundation for estimating load-bearing capacity in real-world scenarios. Further research, incorporating field data and accounting for environmental variables, will be essential for refining this approach and developing more accurate predictive models for autonomous off-road vehicle navigation.

***

### 7125 - A DATA-DRIVEN PARAMETER IDENTIFICATION METHOD OF CHARACTERIZATION OF WHEEL-REGOLITH INTERACTION FOR LUNAR SURFACE VEHICLES

**Authors:** _Hiroaki Kawamura, Tadashi Matsuura, Shinichiro Noda, Kohei Shintani, Nobutaka Tanishima, Natsu Fujioka_

**Key Topics:** Regolith Discrete element method Differential evolution based on adaptive sampling Soil characteristcs Vacuum environment

**Abstract:**

This paper describes a method to clarify the interaction between wheels and regolith particles when a rover runs on the lunar surface. The regolith dust that lifts during movement can adhere to the equipment mounted on the vehicle, potentially causing significant impacts on its functionality. To mitigate the effects of regolith dust on the onboard equipment, it is crucial to understand the behavior of regolith particles that are lifted by the wheels. Additionally, quantitatively understanding the interaction between wheels and regolith particles is important because it affects the wheels' traction and the vehicle's running performance. Many experimental and analytical studies have been published to address this. In the case of numerical analysis, studies using Discrete Element Methods (DEMs) to clarify microscopic interactions have been conducted. To represent the behavior of regolith particles in numerical analysis, it is necessary to identify many parameters that characterize the physical behavior of particles based on test results, which can be time-consuming due to trial and error in deriving these parameters. In this study, a new data-driven set-based searching method, called Differential Evolution Based on Adaptive Sampling (DEBAS), is adopted for the parameter identification of the particles. The proposed method can efficiently find combinations of particle characteristic parameters that match the desired element tests. The parameters obtained through this method will be verified by comparison with several characteristic tests. Furthermore, obtained parameters are validated by comparison with a scaled wheel-regolith simulant interaction test.

***

### 7222 - A SIMULATION FRAMEWORK FOR AUTONOMOUS LUNAR CONSTRUCTION WORK

**Authors:** _Mattias Linde, Daniel Lindmark, Sandra Ålstig, Martin Servin_

**Key Topics:** simulation lunar constriction equipment autonomous earthmoving

**Abstract:**

Planning of lunar construction projects, such as the Artemis Base Camp, is challenging. It includes deciding the design and numbers of different construction machines and how to coordinate them to reach certain time and energy budgets. The machines need to be unmanned to avoid human exposure to the harsh lunar environment. They also need to be highly autonomous due to the poor and delayed communication. Simulation has a central role for finding the necessary solutions for all this.

We present a simulation framework for lunar construction work involving multiple autonomous machines. The framework supports modelling of construction scenarios and autonomy solutions, execution of the scenarios in simulation, and analysis of work time and energy consumption throughout the construction project. A behavior tree manages the operational logic and error handling. High-level decision-making is separated from lower-level control algorithms, with the two connected via ROS2. Machine movements are planned using inverse kinematics. The simulations are based on the physics engine AGX Dynamics that integrates contacting multibody dynamics with deformable terrain.

We present results from a test case that involves an excavator and a dump truck that jointly remove lunar soil to construct a ground shape with a specified 3D profile. The excavator switches between the tasks of digging material from the target area and dumping it on the dumptruck, which has the tasks of receiving material, drive back and forth between the excavation area and dump area, dumping material, and doing levelling at the excavation area usings a blade. All these tasks are in turn be broken down into subtasks, that rely on sensors and controllers. The whole system is represented and managed by a behaviour tree.

***

### 7256 - DATA ASSIMILATION ANALYSIS OF FOOTPAD IMPACT BEHAVIOR OF LANDER ON SOFT GROUND

**Authors:** _Ryuta Kaneda, Masatsugu Otsuki, Shingo Ozaki_

**Key Topics:** Terramechanics Resistive Force Theory Data assimilation Particle filter MMX

**Abstract:**

In FY 2026, the Martian Moons eXploration (MMX) is scheduled to be launched. In the MMX mission, the spacecraft will collect a sample from Phobos, a Martian Moon, to bring back to Earth, and the safe landing of the lander is crucial to the success of the mission. However, the MMX mission and other planned landing missions on low-gravity solid bodies have difficulties in evaluating landing performance in advance using ground experiments and simulations due to uncertainties in the characteristics of the target surface layer. In this study, we examined an estimation method for the surface conditions based on the data assimilation analysis using the collision data of an advance landing probe as a precursor before landing on the main lander. Specifically, we attempted to estimate the stiffness and bulk density of the ground for a drop tower experiment using the footpad of MMX lander, by integrating the collision model based on the resistive force theory and the particle filter. In the drop tower experiments, Phobos-simulated regolith was used as the test soil under quasi-vacuum conditions (less than 100 Pa) and microgravity conditions (1/2500 G). The results of the data assimilation analysis of time series of impact reaction force and settlement under various bulk density conditions indicate that the proposed approach could estimate the initial state of the regolith and the change in state after impact to some extent. However, the accuracy of this particle filter-based estimation method depends on the performance of the collision model (physical model), and it is necessary to use the collision model that can adequately represent realistic phenomena.

***

### 7265 - EVALUATION OF A NEW FRICTION MEASUREMENT DEVICE ON COLD REGIONS TERRAIN

**Authors:** _Sally Shoop, Elder Bruce, Stephen Meurer, Owen Parker, Nathan Kamprath, Don Halliday_

**Key Topics:** Cold regions Arctic Snow Ice Friction Tire Monitoring Tire testing Characterization Winter

**Abstract:**

The RT3 Simplified Curve Unit (SCU) friction tester, by Halliday Technologies, measures surface friction by operating the test wheel at a small side-slip angle. It can be operated at highway speeds and can be used with either aircraft or truck tires and was specifically designed for robust operations in cold environments in the far north. The US Army purchased the Halliday RT3 SCU (SCU) friction tester for use at the Cold Regions Test Center in Alaska, but it was first evaluated for comparison to standard friction test techniques and cold room performance at the Cold Regions Research and Engineering Laboratory in Hanover, NH. Afterwards, it was shipped to Alaska and used on snow and ice test surfaces during March and April of 2025. This paper reports on how the SCU tester measures and reports friction measurement, testing the SCU unit on a wide variety of on- and off-road surfaces, compares the SCU friction measurements to other friction measurement techniques, and reports on the results of cold room testing and operational and exploratory measurements on snow and ice fields in Alaska. A discussion of the measurement technique and results is presented along with conclusions for optimizing use on cold regions terrain surface characterization and monitoring for mobility testing purposes.

***

### 7461 - ADVANCING THE FORWARD LINE OF ROBOTS: A DEMONSTRATION OF INTEGRATED AIR AND GROUND AUTONOMY FOR DYNAMIC MISSION EXECUTION

**Authors:** _Amanda Sgroi, Forrest Johnson_

**Key Topics:** Off-road mobility Autonomous systems Mission Planning Multi-Domain Operations Unmanned Robotic Platforms

**Abstract:**

This white paper presents a joint demonstration by multiple divisions of Applied Research Associates (ARA) showcasing coordinated unmanned ground and aerial systems operating under real-time autonomous mission control. The described demonstration highlights the integration of unmanned ground vehicles (UGVs), unmanned aerial systems (UAS), and Neya’s Mission Planning and Management System (MPMS) to execute a complex, multi-phase mission involving reconnaissance, hazard clearance, autonomous logistics, and dynamic mission replanning. Utilizing MRZR Alphas, ARA’s Sapper robotic ground platform, and mission specific configured drones, the scenario simulates high-risk battlefield conditions to validate the emerging “forward line of robots” doctrine. This concept envisions autonomous systems operating ahead of human forces to enhance survivability, situational awareness, and tactical flexibility. This demonstration illustrates how MPMS enables synchronized autonomy and human-on-the-loop control, supporting seamless transitions across mission phases. Through real-time threat detection, task reassignment, and autonomous response, the demonstration underscores the operational value of heterogeneous robotic teams managed through a centralized control framework. This approach represents a critical capability for future conflict environments where speed, safety, and adaptability are paramount.

***

### 7470 - CONSTRAINT-BASED TERRAMECHANICS SIMULATION FOR REALTIME AND FASTER SIMULATION

**Authors:** _Björn Ahlman, Tomas Berglund, Mikael Lundbäck, Joakim Rydman, Martin Servin_

**Key Topics:** realtime simulation wheel-terrain interaction multibody dynamics deformable terrain

**Abstract:**

We present models and numerical methods for realtime and faster simulation of wheeled and tracked vehicles traversing and interacting with deformable terrain. The wheel-terrain interaction is formulated as a set of kinematic constraints with constraint forces and limits that reflect the stresses on the wheel and soil failure at critical stresses. When soil failure occurs, a 3D soil displacement field is predicted and used to update the spatial distribution of soil, local packing density, and the surface heightmap. The constraint-based formulation enables stable and strong coupling between the terrain and vehicle multibody dynamics at large time-steps. Simulation tests are performed where the implemented model is compared to experiments and standard semi-empirical terramechanics models. Finally, we apply the terramechanics model on a model of a heavy forest machine traversing rough terrain and study how the motion and dynamic load forces are affected by inclusion of deformable terrain.

***

### 7475 - VALIDATION OF EXPERIMENTAL TERRAMECHANICS MODELLING APPROACHES THROUGH PHYSICAL TESTING

**Authors:** _Eric Karpman, Jozsef Kovecses, Marek Teichmann_

**Key Topics:** Terramechanics Off-Road Machine Learning Uneven Terrain Simulation Experimental Validation

**Abstract:**

The traditional semi-empirical terramechanics models have been heavily relied on over the past decades. Despite the fact that their numerous assumptions limit their applicability in certain scenarios. In particular, the real forces in transient states can results in behaviour that is not captured by the semi-empirical models. Additionally, the models are formulated with the assumption that the wheel or track is travelling over flat, level terrain. We have previously proposed two separate methods for adapting the models to address these two specific shortcomings. For the former, we proposed a hybrid modelling approach which uses trained neural networks to augment the force predicted by the semi-empirical models. Using this approach, we do not discard the valuable insight that the established models provide, but are still able to capture some dynamic and transient behaviour. For the later shortcoming, we proposed a novel variable terrain height adaptation of the semi-empirical model which computes stresses at each point along the wheel-soil interface by projecting that point in space onto the heightfield that defines the terrain. This is in contrast to other established methods for handling uneven terrain by defining least squares planes which are meant to approximate the terrain geometry, but which in practice can have the effect of smoothing out terrain roughness. In order to validate these two proposed models, an experimental test campaign was carried out in which an instrumented off-road vehicle underwent a drawbar-pull test on soft terrain, and a second test in which the same vehicle was driven over a sand course with an uneven surface profile. The results of these two sets of experiments are used to justify the modelling approaches we have proposed.

***

### 7559 - DYNAMIC CONTACT PATCH ESTIMATION FROM 3D CONTACT PATCH MEASUREMENTS INSIDE A MOVING TYRE UNDER COMBINED SLIP CONDITIONS

**Authors:** _Amal Patel, Schalk Els_

**Key Topics:** Digital Image Correlation Tyre Contact Patch Slip Angle Pressure Distribution Dynamic Rolling Radius Terrain Deformation Contact Patch Velocity Intelligent Tyres

**Abstract:**

Vehicle stability is inherently related to tyre-terrain interaction. Slip conditions arising from tyre forces generated due to the terrain and vehicles state is a valuable indication of a vehicle’s stability. Measurement and analysis of the tyre contact patch is complex, yet abundant information can be derived from contact patch measurements. Literature indicates that analysis of the contact patch is difficult, and indirect methods are used to determine tyre states under ideal conditions of paved roads. Few researchers attempt to directly analyse the contact patch and extract key tyre states: slip angle, pressure distribution, terrain deformation, contact patch velocity and dynamic rolling radius. This study uses the T2Cam apparatus, a mechanism that fits into a tyre and provides the capability to attach cameras inside the wheel that remain stationary despite the tyre rotating. The use of T2Cam and an RGBD camera provides the capability of a non-contact method using DIC (Digital Image Correlation) to measure tyre contact patch deformation and relate that to key tyre states. The purpose of this study is to develop algorithms to extract key states from contact patch deformation of the inside of the tyre carcass under varying tyre conditions. Preliminary findings show tyre deformation of the contact patch is measurable and accurate to be used as an input in an algorithm to calculate slip angle, contact patch velocity and dynamic rolling radius. Overall, determining these factors will enhance the understanding and visualisation of the dynamic contact patch and prediction of vehicle stability on many types of terrain.

***

### 7714 - THE ROLE OF THE EVANESCENT SLOW WAVE IN NON-CONTACT MOISTURE MEASUREMENT OF FIELD TRAFFICABILITY

**Authors:** _Zhihe Jin, Joseph Dvorak, Michael Peterson_

**Key Topics:** Sand Moisture Acoustic Slow-wave

**Abstract:**

The moisture content of soil is the single most important factor for trafficability of fields. Many sensing technologies are limited to surface moisture such as optical techniques or may be sensitive to variation in texture or salinity. Elastic wave methods are more likely to be sensitive to the mechanical properties of the soil and are directly related to the trafficability of the surface. Acoustic methods are also not impacted by the crowding of the electromagnetic spectrum.

Previous investigators have considered the use of acoustic sensing for moisture and hardpan depth. However, the transfer of this research into applications has been limited. This work is initially focused on characterizing the underlying physics of waves in porous media at a length scale applicable to sandy soils with a narrow pore size distribution. These soils are well suited to this investigation because of potential importance of the slow wave in for moisture detection. The slow longitudinal wave has been used extensively in other areas such as geophysics and membrane characterization. The pore size in sandy soil would not lead to propagation of a slow wave at practical sensor frequencies. However, an evanescent slow wave will impact the effective acoustic impedance of the soil air interface. The energy transfer to the evanescent wave will depend on the portion of the pore structure that is filled with water instead of air.

A model for reflection from a porous interface is formulated for a narrow distribution of pore sizes. Sensitivity of the model to different water content and the effect of frequency on the depth of penetration are considered. Simple experiments with a model soil are used to validate modeling, explore sensor configurations and proposes sensor field deployment.

***

### 8096 - VISION LANGUAGE ACTION MODELS ON UNMANNED GROUND VEHICLES

**Authors:** _James Adams, Collin Otis, Colby Adcock_

**Key Topics:** Vision language action model UGV Autonomy Low SWaP-C Passive Sensing Edge compute

**Abstract:**

Scout AI is developing an end-to-end learned autonomy system for unmanned ground vehicles (UGVs) with the objective of executing complex missions from a commander’s intent, desired endstate, and broader mission context.

The system centers on a Vision-Language-Action Model (VLA) trained through reinforcement and imitation learning to enable adaptive control, situational reasoning, and contextual understanding in off-road, GPS- and comms-degraded environments.

Scout’s autonomy operates as a retrieval-augmented generation (RAG) loop, continuously querying the VLM with real time inputs from sensor data and fuses them with prior state, and mission context to drive high-level decision-making and low-level execution to generate navigation and control outputs in real time. The autonomy stack integrates passive modular perception from a single RGB camera delivering end-to-end localization, planning, and control, optimized for low SWaP-C platforms and unstructured terrain.

Field-tested at TRL 7 across an offroad UGV platform, the system has demonstrated robust terrain traversal, dynamic replanning, and waypoint navigation, supporting the broader vision of human-commanded, independently operating ground robots.

***

### 8140 - NUMERICAL MODELING OF PLATE SINKAGE AND IN SITU BEVAMETER SHEAR TESTING USING FEM AND THE DENSITY-DEPENDENT NORSAND CRITICAL STATE CONSTITUTIVE SOIL MODEL

**Authors:** _Ray Kruger, Petrus Arnoldus Crous, Yuderka Trinidad Gonzalez, Mehari Tekeste_

**Key Topics:** Plate Sinkage In Situ Shear Tests Bevameter Critical State Soil Mechanics (CSSM) Finite Element Method (FEM) NorSand Constitutive model

**Abstract:**

The Bekker-Wong terramechanics model remains a cornerstone for predicting wheel–soil interactions, relying on Bevameter tests to characterize soil behavior via plate sinkage and in situ shear tests. However, accurately modeling these tests, and the underlying physics, remains challenging. Physics-based methods like the Discrete Element Method (DEM) lack key critical state soil mechanics features such as density dependence, yield functions, and pore pressure effects. This study employs an implicit, large-strain Finite Element Method (FEM) formulation and the NorSand critical state model to simulate plate sinkage and shear testing in partially saturated Cullinan sand. NorSand captures soil behavior through evolving yield surfaces and stress–dilatancy relationships linked to effective stress, void ratio, and density-dependent strength. Density-dependent shear resistance is captured by linking state parameters to increased mobilized friction ratios. Parameters were calibrated using 18 CU and CD triaxial tests via an automated Bayesian optimization scheme. Validation against field Bevameter experiments was performed in a forward-only modeling approach. The model shows good agreement with in situ shear tests, capturing peak shear strength and post-peak softening behavior across a range of densities. Plate sinkage predictions match early-stage stiffness but diverge at large settlements due to numerical instability. Numerical results demonstrate good agreement with experimental data, successfully capturing the soil density trends and deformations up to the pre-failure region.

***

### 8342 - EFFECT OF SNOW SUBDUCTION ON VEHICLE MOBILITY

**Author:** _Mark Bodie_

**Key Topics:** snowplowing motion resistance traction mobility sinkage

**Abstract:**

Winter surfaces are characterized by low strength, which can result in deep vehicle sinkage and high vehicle motion resistances. If the vehicle’s sinkage is greater than the vehicle’s ground clearance, snowplowing forces occur, further increasing the vehicles motion resistance. The increased motion resistance can lead to vehicle immobility if the vehicle’s available traction is exceeded. In this work we investigate the effect of snow subduction on vehicle mobility. When snowplowing occurs a portion of the plowed snow can be subducted under the vehicle’s belly. The subducted snow is compressed resulting in both an increase in motion resistance and a normal load reduction under the vehicle’s track or tire. We developed an algorithm which includes both snow subduction effects on the vehicle’s mobility. In the study we found that the snow subducted under the vehicle has a substantial effect on the vehicle’s mobility. We simulated a 103kPa ground pressure vehicle with 0.1m snow subduction zone. When snow subduction was included in the analysis, we found that vehicle immobility occurred at a snow depth of 0.59m as compared to a depth of 0.7m when subduction was not included. The large variation in snow depth at vehicle immobility, underlines the importance of including snow subduction in vehicle mobility and route planning analyses. In future work we will improve the accuracy of the algorithm by incorporating snow stratigraphy. The current algorithm uses bulk density to determine snow strength, in future analyses we will incorporate snow layer density and grain size to improve the algorithms accuracy.

***

### 8352 - ASSESSING THE STRENGTH OF RIVER BOTTOMS FOR VEHICLE FORDING

**Authors:** _Sally Shoop, John Eylander, Theodore Letcher, Kathleen Staebell_

**Key Topics:** River Crossing Fluvial Geomorphology Gravel Strength Low Water Crossing River Sediments River Bottom Grain Size Wet Gap Crossing Measurement Vehicle Fording

**Abstract:**

Vehicle fording, a means of wet gap crossing, is difficult to study because of numerous requirements to ensure safe crossing based on both the vehicle and the changing characteristics of the river. While some of these requirements are well-known, others are so complex and variable that they remain ill-defined. This paper will review river crossing guidance with a special interest on river characteristics that are seasonally variable. While seasonal changes in river flow rate are somewhat predictable, they rely on many assumptions about the river bathymetry and discharge. The riverbank conditions can also change drastically with season, affecting ingress and egress. Lastly, the competence of the river bottom (strength and stability) is extremely difficult to estimate remotely or to measure, so this was a primary focus for this research. Recent progress in fluvial geomorphology and the new field called river morphodynamics may help in determining the best places to cross a river based on its adjacent landforms, river type, and available site observations. Equations from fluvial geomorphology and geotechnical engineering are used to relate river conditions to bottom sediment strength. Exploratory field measurements of river bottom strength were performed. Results using a modified static cone penetrometer were analyzed and methodology to evaluation the strength of the river bottom was developed. While data requires extra care to interpret, the results shed light on areas of future research needs. Fording guidance, applicable geomorphology, and recent advancements in terramechanics research for river crossings are summarized to provide context. Field methods, results and future research needs are presented.

***

### 8595 - MOVEMENT ENVIRONMENT ASSESSMENT AND FORCE PREDICTION FOR QUADRUPED ROBOTS

**Authors:** _Zhen Chen, Yuzhi Wang, Lutz Oliver Richter, Meng Zou_

**Key Topics:** Quadruped robot Locomotion process Force prediction Contact state determination

**Abstract:**

Assessing the operating environment of a quadruped robot and analyzing the forces acting on its footpads are crucial for enhancing motion stability and enabling effective path planning, ultimately ensuring successful task completion. This study focuses on analyzing the robot's motion state and its contact process to better understand its contact dynamics and develop a comprehensive dynamic model. The model defines the relationship between footpad forces and joint angular torque, enabling both environmental assessment and force prediction. Experimental validation was conducted using the quadruped robot in various environments, confirming the model's effectiveness. By comparing the joint angular torque during contact and non-contact states, the footpad contact conditions were determined. During the contact phase, joint angular torque exceeded the non-contact torque, with greater discrepancies corresponding to higher footpad forces. These findings suggest that denser soil improves the robot’s performance. The method for calculating footpad forces from torque demonstrated an accuracy exceeding 90%, highlighting its precision. These results provide valuable insights for calculating operational forces, as well as for the stability assessment and trajectory planning of quadruped robots.

***

### 8964 - APPLICATION OF LSTM NETWORKS TO REAL-TIME PREDICTION OF A WHEEL TRAVELING PHENOMENA

**Authors:** _Haruki Endo, Shingo Ozaki, Kai Xing_

**Key Topics:** Wheel Trafficability Simulation Deep learning LSTM network

**Abstract:**

Lunar exploration, which began in the 1960s, is still ongoing and various space exploration programs are planned. In these space exploration programs, it is important to analyze and predict the trafficability of exploration rovers on the lunar and Martian surfaces, and to develop and operate on these ground conditions. Therefore, in this study, we focused on the real-time analysis in operational phase of exploration rovers. We applied a Long Short-term Memory (LSTM)1) network, an artificial regression neural network architecture used in the field of deep learning, to single-wheel traveling phenomena with the aim of applying it to the real-time prediction in future exploration rover operations. Specifically, numerical simulations were carried out using an extended terramechanics model that takes terrain surface deformation into account, and training and prediction are carried out on several LSTM models. The results show the possibility of real-time prediction of trafficability of a wheel on soft ground due to the characteristics of LSTM networks that can handle time-series data. Furthermore, it is suggested that the proposed method may be applicable to the prediction of precursor phenomena of wheel stuck.

1. Gonzalez, J ; Yu, W. Non-linear system modeling using LSTM neural networks. IFAC-Pap. 2018, 51, 485-489.

***

### 8969 - SURVEY OF LIDAR EFFECTS FOR AUTONOMOUS DRIVING SIMULATIONS

**Authors:** _John Kaniarz, Brian Brady, Laura Walizer, Phillip Price, Mike Parker_

**Key Topics:** LiDAR simulation autonomous fidelity

**Abstract:**

A wide variety of software packages are available for modeling Light Detection and Ranging (LiDAR) sensors in the context of autonomous driving simulations. This report highlights ten effects that a high-fidelity LiDAR simulation should be capable of delivering. Examples are provided from real-world data collected in the field, synthetic results generated in simulation, and published literature. Simulation users must carefully consider performance versus fidelity tradeoffs when selecting a suitable LiDAR simulation package for use

***

### 9165 - SIMULATION OF THE RELATIONSHIP BETWEEN THE DECREASED BEARING CAPACITY WHILE IMPARTING VIBRATION TO GROUND AND VIBRATION FREQUENCY IN THE DISCRETE ELEMENT METHOD

**Authors:** _Tomohiro Watanabe, Dai Watanabe, Kojiro Iizuka_

**Key Topics:** discrete element method bearing capacity planetary exploration vibration

**Abstract:**

Recently, moving underground has been focused on as a method of planetary exploring robots' movement.　Exploration rovers have difficulty moving underground because the drag force from the ground restricts their movement, hindering underground exploration. A previous study developed a mechanism that moves underground by imparting vibration to the ground and decreasing the drag force. The experimental results demonstrate the superiority of the proposed method, as the movement distance achieved with vibration is considerably greater than without vibration. The optimal vibration should be selected to improve the proposed mechanism's underground mobility. When imparting vibration, the change of the bearing capacity, which is the resistance from the ground, depends on lift-off acceleration. Lift-off acceleration is the minimum vibration acceleration that causes the flow of the ground particles. The bearing capacity increases when the rod's movement is under lift-off acceleration. Conversely, it decreases when the rod's movement is over lift-off acceleration. If the simulation reproduces the change of the bearing capacity when imparting vibration and lift-off acceleration, the optimal vibration can be selected. This study conducted the experiment and the DEM simulation in which the rod is dragged while vibrating on the ground. These methods measured the bearing capacity that the rod received from the ground. In the experiment and simulation, the vibration frequency was changed. As the vibration frequency increases, the acceleration of the rod's movement caused by the vibration eventually exceeds the lift-off acceleration. The reproducibility of DEM simulations was evaluated by comparing the relationship between the bearing capacity and vibration frequency in each method.

***

### 9326 - SNOW PLATE INDENTION STUDY

**Author:** _Mark Bodie_

**Key Topics:** snow strength sinkage snow stratigraphy mobility

**Abstract:**

Snow strength is an important factor in vehicle mobility. A high snow strength route can be trafficable, while the same route with low snow strength can result in large vehicle sinkage and immobility. In this work we generate sinkage and compression energy models from snow layer density and grain size. The models were informed from measurements taken from a snow indention device we developed. The device measures virgin snows stress strain characteristics in snowpacks up to 2m deep. The device was design to be mobile, attaching to an over-snow-vehicle, with an indention plate area, 0.03m2, relevant to tire or track contact areas. Initial snow indention measurements were taken at Grand Mesa, CO. These measurements were compared to predictions from the enhanced sinkage and energy compression models as well as to legacy models. In future work, we look to measure additional snowpacks using the plate indention device to increase the enhanced model’s prediction accuracy.

***

### 9360 - OPTICAL VELOCITY AND SLIP ESTIMATION FOR OFF-ROAD UGV CONTROL

**Authors:** _Glenn Guthrie, Andries Peenze, Schalk Els_

**Key Topics:** stereo camera ugv vehicle velocity longitudinal slip robot unmanned stability control slip control

**Abstract:**

In vehicle dynamics, the measurement of accurate vehicle velocity (magnitude and direction) using low-cost sensors is a significant challenge, yet this measurement is extremely valuable as an input for vehicle control systems. Traditional low-cost methods for measuring vehicle velocity often rely on dual antenna GPS algorithms that have reduced accuracy at low speed and GPS reception is often challenging in varied environments. This work applies an optical technique to measure the longitudinal and lateral velocities required to calculate slip using a downward facing depth camera (Intel Realsense) to capture images and a point cloud of the terrain surface. The images and point cloud are processed by a feature tracking algorithm and the vehicle velocity is calculated based on the relative motion of the ground and vehicle body. The technique is applied to a four-wheeled, skid steer, off-road, unmanned ground vehicle (UGV) that frequently encounters low-traction conditions while operating on slippery and uneven terrain. This suspensionless UGV has electric servo motors driving each wheel independently, allowing both measurement and control of wheel speed and torque. The calculated vehicle velocity is combined with wheel speeds from the motors to calculate individual longitudinal wheel slips. The measurement technique’s performance is evaluated by using the vehicle velocity and longitudinal wheel slip in a control algorithm that is designed to maintain a desired vehicle attitude even when wheel slip occurs. The slip measurement technique and control algorithm are evaluated by driving the vehicle on low friction and split friction surfaces while recording the desired attitude and actual vehicle attitude.

***

### 9467 - SAMPLING CONTROL STRATEGY FOR MARTIAN SURFACE EXCAVATION AND SAMPLING TASKS

**Authors:** _Hongtao Cao, Meng Zou, Jianqiao LI, Haoran Xie, Jiangquan LI, Yan Shen_

**Key Topics:** Excavation force prediction Robotic arm control Real-time sampling risk prediction

**Abstract:**

The Martian surface is densely covered with rocks, and the communication delay between Earth and Mars can extend to several tens of minutes, making autonomy, intelligent control, and real-time risk prediction critical challenges for excavation and sampling tasks. This study proposes a Hybrid Deep Reinforcement Learning (HDRL)-based framework for Martian soil sampling prediction and control. By integrating soil mechanics physics with data-driven strategies, the framework achieves closed-loop integration of dynamic excavation force prediction, autonomous robotic arm control, and real-time risk assessment. A multi-scenario model library was constructed through high-fidelity Discrete Element Method (DEM) simulations, and a hierarchical HDRL architecture was developed using rigid-flexible coupled dynamic modeling and training datasets. The control strategy was optimized via a multi-objective reward function (sampling efficiency weight: 0.6, energy consumption weight: 0.3, collision penalty weight: 0.1). Experimental results demonstrate that the HDRL framework achieves a sampling success rate exceeding 90%, reduces collision probability to below 5%, and maintains generalization errors under 10% for untrained geological conditions. This method provides a highly robust solution for autonomous sampling in Mars' complex environments.

***

### 9563 - PHYSICAL TESTING AND DIGITAL TWIN SIMULATIONS FOR PREDICTION OF RIDE QUALITY OF LIGHT UTILITY VEHICLE

**Authors:** _Eric Karpman, Wei Huang, Nikita Yovchev, Patrick Kehoe_

**Key Topics:** Ride Quality. Rough Terrain. Off-road. Simulation. Vibration Testing.

**Abstract:**

Ride quality is an important metric for assessing the comfort and safety of vehicle passengers as a vehicle traverses rough off-road terrain. One common approach for assessing ride quality is the Absorbed Power metric, which sets a power threshold below which a crew member can effectively perform their tasks. The roughness of the terrain itself is characterized by the root mean square (RMS) value of the terrain profile as per TOP-1-1-014. Using an accelerometer to measure the acceleration experienced by the passengers, a series of tests can be conducted in which the vehicle and traverses a given course at constant speeds, increasing the speed with each traversal. By calculating the absorbed power at each speed, a maximum allowable speed can be determined for a given course. Because it is not always possible to take a vehicle into the field to test it on such a course, vibration testing using a four-post shaker to emulate the terrain profile can be used as an alternate test to assess the ride quality. In this work, we perform vibration testing on a light utility vehicle in an effort to assess ride quality over an asymmetric 3cm RMS terrain. Additional physical testing – including a tilt test to determine center of gravity height – were performed to tune a digital twin of the vehicle. The same suite of tests was performed on the digital twin in a virtual environment and compared to the physical test results. The virtual test of the vehicle traversing the 3cm RMS course that the vibration test emulates was also performed on the digital twin to compare vibration testing results to that of a fully modelled traversal of the terrain.

***

### 9668 - INNOVATING MOBILITY: A STUDENT COMPETITION IN WHEEL AND TRACK DESIGN

**Authors:** _Devin Chen, Chaitanya Shekhar Sonalkar, Riku Kikuta, Andries Peenze, Varsha S Swamy, John Ethan Salmon, Bohumir Jelinek, George Mason, P. Schalk Els, Corina Sandu_

**Key Topics:** Terramechanics Off-road mobility Hands-on/Experiential Learning ISTVS student competitions Rapid Prototyping

**Abstract:**

In this paper, we propose a new initiative for the ISTVS Wheel/Track Design Student Competition, aimed at engaging students in terramechanics and providing hands-on experience in off-road wheel/track design and testing. The competition will challenge student teams to design and fabricate a wheel or track system for a small vehicle, which will then undergo a series of tractive performance and mobility tests in selected soil types. By minimizing costs and focusing on practical, accessible design and testing methods, the competition ensures that students from various backgrounds and disciplines at any interested university can participate.

The competition will include design presentations and performance tests, evaluated using structured scoring criteria. To support accessibility, teams can use freely available CAD software, 3D printing, and other rapid prototyping techniques.

The performance evaluation will be conducted using a test matrix that examines both structural integrity and performance metrics, which may include slope tests, measurement of drawbar pull, sinkage versus slip, lateral forces in turn, and slope climbing characterization in alignment with ISTVS standards. A single-wheeled terramechanics test rig will assess the wheel/track performance in controlled environments, optionally supplemented by the small-vehicle based mobility tests under various soil conditions in the field. Through this competition, students will gain valuable experience, develop innovative solutions, and develop connections to ISTVS, fostering the next generation of terramechanics engineers.
