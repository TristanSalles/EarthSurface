Fluvial sediment transport
==========================================

..  admonition:: Chapter structure
    :class: toggle

    - Forces involved in sediment transport
    - Settling velocities and entrainment thresholds
    - Types of sediment transport
    - Sediment transport rates

Fluvial sediment transport is the study of the interaction between channelized, unidirectional flows of relatively clear water and natural, generally non-cohesive, sediment.

In this chapter we will discuss 1) the forces governing the settling and movement of grains in a fluid, 2) the approaches used to predict the threshold of movement and 3) the different ways transported sediments will be moved by the flow once the threshold of movement has been exceeded.

..  admonition:: Learning outcomes
    :class: toggle

    - Understand, conceptually, the processes involved in sediment transport
    - Appreciate the role of sediment transport processes in landform development


.. figure:: images/Hjulstromdiagram.png
   :scale: 65 %
   :alt: Hjulstrom diagram of sediment transport by running water
   :align: center

   Hjulstrom diagram of sediment transport by running water



Fluid flow and flow properties
-------------------------------


Flow types
************************************************

Much of what we understand concerning sediment transport is based on a series of fundamental concepts in fluid mechanics. Therefore to understand sediment transport, it is essential to understand the mechanics of fluid flow.

.. important::
  There are two end member ways fluids flow: 1) **laminar flow** and 2) **turbulent flow**. There is a wide gradation between these two end members, specifically **transitional** flows.


.. figure:: images/laminar-and-turbulent-boundary-layers-24.png
  :width: 100 %
  :alt: Different plates
  :align: center


**Laminar Flow** - In laminar flow, water molecules move in straight, parallel lines down current. If you add a dye to water that is in the laminar flow regime, the dye would not mix into the water; it would streak out in an approximately straight line. Laminar flow is characteristic of very slow moving, shallow water, which is uncommon in nature. It is also characteristic of flows in "fluids" that are very viscous, like glacial ice or mud flows that have little water.

**Turbulent Flow** - In contrast, turbulent flow is characterised by complex motion of water (or other) molecules. Molecules move in all directions in bursts of upward, downward, and forward motion, and even some backward movement. There is abundant mixing in the flow because neighbouring molecules move in different directions, and an added dye mixes into the water very quickly. Most water and air flows are turbulent, at least to some degree. Turbulence is important for sediment transport because it makes grains easier to transport and tends to keep them moving longer.

**Transitional Flow** - Transitional flows have some characteristics of laminar flow and some of turbulent flow. For example, dye may take some time to mix into the flow, but it does mix.



Reynolds Number
************************************************

The Reynolds number predicts the extent of turbulence in a fluid based on how fast the fluid is flowing, the geometry of the flow (how deep and wide it is, etc.), and the density and viscosity the of the fluid.

[Viscosity is a measure of the resistance of a material to flow, i.e. how “thick” and easily deformed it is. Viscosity is sort-of like the amount of friction within a substance. Walking through air is easy, because there is not much friction between air molecules. Air has a low viscosity. Swimming is more difficult because the water drags on your body. This is due to the “friction” between adjacent water molecules, i.e. higher viscosity. Ice is more viscous and impossible to move through because of the crystal bonds between the water molecules. It flows, but it does so slowly. ]

Back to the Reynolds number. The variables for the Reynolds number (Re) are: flow velocity (u), characteristic length (l) which represents flow geometry, say river depth, fluid density (ρ), and fluid viscosity (µ). The book uses µ/ρ = v (kinematic viscosity). Re = (fluid inertial forces)/(fluid viscous forces) = l*u*ρ/µ. The units for this equation are typically (length)*(length/time)*(mass/length3) / (mass/(length*time)). These all cancel out to form a unitless number, if you choose the same set of units for each variable, which you should always do.

Re can be viewed as inertial forces divided by viscous forces. Inertia is the resistance to change in motion, and inertial forces tend to make a bit of the fluid keep flowing in its own direction if it is misdirected from the main flow direction. Thus, high inertial forces tend to cause more turbulence. In contrast, viscous forces tend to suppress turbulence by damping out variations in motion through friction. Thus, a flow with a high viscosity (ice) tends to have less turbulence than a low viscosity flow (air).

The magnitude of Re gives an idea of whether the flow is turbulent or laminar. Turbulent flow has Re greater than 2000 and laminar flow has Re less than500. Flow with Re between 500 and 2000 is transitional and has some characteristics of laminar flow, but some turbulence as well. In most cases, water and air flows have high Re because l is large, u is high and µ is low. Rivers and wind storms are good examples of turbulent flow. In contrast, ice has a large µ and flows slowly (u is low), so it is usually laminar. Also, very thin, slow flows of water, such as water flowing off a smooth cement parking lot, has a low Re because l and u are small. Thus, it can be laminar. Laminar flow also occurs locally in turbulent flows right at the contact between the fluid and a smooth surface it is flowing over because u becomes very slow. This is really important for sediment transport, and we'll talk more about it in a few minutes.

It is useful to think about which variables are important for different comparisons. When comparing ice and water, the main difference is viscosity; the viscosity of ice is >10^3 kg/(m*s) and up to more than 10^20 kg/(m*s) depending on temperature. In contrast, the viscosity of water is ~10^-3 kg/(m*s). The density of both is very close to 1000 kg/m^3. Thus, ice is almost always laminar but water is usually turbulent, although it can be laminar. When considering water flows, the flow speed and water depth are both very important. The viscosity and density change a little bit with temperature, but variations in flow speed and water depth are typically much larger effects.

Images of glaciers:
low viscosity (for a glacier): http://visibleearth.nasa.gov/view_rec.php?id=16438
high viscosity: http://tinyurl.com/yhyrob9

For air, both the density and viscosity are low, so does Re tend to be high or low? The density of dry air at 1 atm at 15°C is 1.225 kg/m3, and its viscosity is 1.8x10^-5 kg/(m*s), giving p/µ=6.8x10^5 s/m2 for air versus 1.0x10^6 s/m2 for water. Thus, air would tend to have a lower value for Re than water. However, the thickness of typical air flows (meters to 100’s of meters) promotes turbulence. p/µ for ice is 1 to 10^-17, which is why it is essentially always in a laminar flow regime.

Boundary Layer - There is boundary layer at the edge of every flow. Flows have an average speed in the middle, but friction with immobile surfaces slows down the speed of the flow right at the surface. This creates a boundary layer that has different flow characteristics than the rest of the flow. Right at the surface, the water does not move, but as you go higher into the flow it starts to move more like the average flow. The area of the flow that has a reduced speed is called the boundary layer. The thickness of the boundary layer depends on Re (i.e. the amount of turbulence) and the roughness of the surface the flow is moving past. If the main water flow is very turbulent, it changes the velocity distribution because more of the high speed water is mixed down into the lower speed areas. Thus, the boundary layer tends to be thin. In less turbulent flow, there is little mixing of water from the center of the flow toward the edge of the flow, so the boundary layer tends to be thicker.

Viscous/Laminar Sublayer - Within the boundary layer, right next to the surface, the laminar sublayer is present. Re=u*l*ρ/µ - remember this defines the difference between laminar and turbulent flow. Because u (water speed) is very low at the base of the boundary layer, the Re is low there and the flow is laminar. The laminar flow part of the boundary layer is called the viscous or laminar sublayer, “viscous” because the viscous effects are more important than the inertial effects. (The fluid is NOT more viscous here.) Farther up in the flow, u is higher, so the flow is typically turbulent. If grains do not extend above the top of this layer, they do not “see” much turbulence, and they are less likely to be transported. If they do stick up beyond the viscous sublayer because the viscous sublayer is thin or the grains are large, the grains feel the force of the turbulent flow.

Bed roughness or the characteristics of the surface also affect the boundary layer by affecting the amount of water that has to interact with the surface. A very smooth bed, say one made of mud, does not deflect the water at all, so there is less mixing and less turbulence. There is a well developed laminar sublayer. In contrast, a bed with pebbles or boulders disrupts the direction of water flow in the boundary layer. The water gets deflected around the pebbles. Water from above tends to take its place. Since it is moving faster, the average water speed in the boundary layer increases. Thus, a rough bed reduces the thickness of the boundary layer much like a more turbulent flow does. A rough bed also disrupts the laminar sublayer by forcing the flow to move around objects. The laminar sublayer is developed locally, but in general, rough beds are very turbulent.

The boundary layer in a flume:


Sediments and Flow
Key Concept: The boundary layer strongly affects the amount of “Bed Shear Stress” which corresponds to the forces that tend to roll particles along the bed and the pressure differences above and below grains, which tend to lift them off the bed.

Bed Shear Stress - Sediments are affected by the difference in flow speeds from the bottom to the top of the boundary layer, gravity, and friction with the ground. Bed shear stress is a measure of these differences; it is the differential force that a grain feels from top to bottom. In a thick boundary layer, the speed of water flow at the top of the grains is not much different from the bottom, so bed shear stress is lower, and sediment is less likely to move. In a thin boundary layer, bed shear stress is much higher, and grains are likely to roll down flow. Thus, more turbulent flow (with a thinner boundary layer) results in more sediment transport. Bed shear stress increases with increasing fluid density, slope, and turbulence (water depth and flow speed). For example, water is better at moving sediment than air because it has a higher density and exerts a larger bed shear stress than air can. Deep, fast rivers move more sediment than shallow, slow rivers because of more turbulence and higher flow speeds in the boundary layer in fast rivers.

Some definitions
*******************


Sediment transport is critical to understanding how rivers work because
it is the set of processes that mediates between the flowing water
and the channel boundary. Erosion involves the removal and transport
of sediment (mainly from the boundary) and deposition involves the
transport and placement of sediment on the boundary. Erosion and
deposition are what form the channel of any alluvial river as well as the
floodplain through which it moves.

The amount and size of sediment moving through a river channel are
determined by three fundamental controls: competence, capacity and
sediment supply.

Competence
^^^^^^^^^^^^^^^^^^^^^^^^^^

**Competence** refers to the largest size (diameter) of sediment particle or grain that the flow is capable of moving; it is a hydraulic limitation. If a river is sluggish and moving very slowly it simply may not have the power to mobilise and transport sediment of a given size even though such sediment is available to transport. So a river may be competent or incompetent with respect to a given grain size. If it is incompetent it will not transport sediment of the given size. If it is competent it may transport sediment of that size if such sediment is available (that is, the river is not supply-limited).

Capacity
^^^^^^^^^^^^^^^^^^^^^^^^^^

**Capacity** refers to the maximum amount of sediment of a given size that a stream can transport in traction as bedload. Given a supply of sediment, capacity depends on channel gradient, discharge and the calibre of the load (the presence of fines may increase fluid density and increase capacity; the presence of large particles may obstruct the flow and reduce capacity). Capacity transport is the competence-limited sediment transport (mass per unit time) predicted by all sediment transport equations, examples of which we will examine below. Capacity transport only occurs when sediment supply is abundant (non-limiting).

Sediment supply
^^^^^^^^^^^^^^^^^^^^^^^^^^

**Sediment supply** refers to the amount and size of sediment available for sediment transport. Capacity transport for a given grain size is only achieved if the supply of that calibre of sediment is not limiting (that is, the maximum amount of sediment a stream is capable of transporting is actually available). Because of these two different potential constraints (hydraulics and sediment supply) distinction is often made between supply-limited and capacity-limited transport. Most rivers probably function in a sediment-supply limited condition although we often assume that this is not the case.

Much of the material supplied to a stream is so fine (silt and clay) that, provided it can be carried in suspension, almost any flow will transport it. Although there must be an upper limit to the capacity of the stream to transport such fines, it is probably never reached in natural channels
and the amount moved is limited by supply. In contrast, transport of coarser material (say, coarser than fine sand) is largely capacity limited.


Sediment transport
*******************

The sediment load of a river is transported in various ways although these distinctions are to some extent arbitrary and not always very practical in the sense that not all of the components can be separated in practice:

1. Dissolved load
2. Suspended load
3. Intermittent suspension (saltation) load
4. Wash load
5. Bed load


.. figure:: images/transport.jpg
   :scale: 70 %
   :alt: Sediment transport
   :align: center

   Sediment transport stages regarding the hydrologic, hydraulic, and geomorphological conditions: adopted from Marshak 2005.

Dissolved load
^^^^^^^^^^^^^^^^^^^^^^^^^^

**Dissolved load** is material that has gone into solution and is part of the fluid moving through the channel. Since it is dissolved, it does not depend on forces in the flow to keep it in the water column.

In sediment-transport theory an important distinction is made between dissolved material and clastic material. Clastic material is all the particulate matter (undissolved material) carried by a river regardless of the grain size. The clastic load of a river is moved by several mechanisms that are the basis for recognizing the two principal sediment transport modes: *suspended-sediment load* and *bed-material load*.

Suspended-sediment load
^^^^^^^^^^^^^^^^^^^^^^^^^^

**Suspended-sediment load** is the clastic (particulate) material that moves through the channel in the water column. These materials, mainly silt and sand, are kept in suspension by the upward flux of turbulence generated at the bed of the channel. The upward currents must equal or exceed the particle fall-velocity for suspended-sediment load to be sustained.

The size and concentration of suspended-sediment typically varies logarithmically with height above the bed. That is, concentration and grain size form linear plots with the logarithm of height above the bed. Coarse sand is highly concentrated near the bed and declines with height at a faster rate than does fine sand. Fine silt is so easily suspended that it is far more uniformly distributed in a vertical section than is the coarser material. Similarly, the grain-size distribution within a sample of sand displays far more vertical variation than does the vertical distribution of grain size within the silt range. The former is too large for the flow to move much of it into the upper water column and the latter is so small and easily suspended that it is well represented at all levels thus giving rise to a more uniform grain-size profile.

.. figure:: images/profiles.png
   :scale: 32 %
   :alt: vertical profiles
   :align: center

   Typical vertical profiles of suspended-sediment concentration (A) & grain size in open-channel flows (B)

Wash load
^^^^^^^^^^^^^^^^^^^^^^^^^^

Although **wash load** is part of the suspended-sediment load it is useful here to make a distinction. Unlike most suspended-sediment load, wash load does not rely on the force of mechanical turbulence generated by flowing water to keep it in suspension. It is so fine (in the clay range) that it is kept in suspension by thermal molecular agitation (sometimes known as Brownian motion, named for the early 19th century botanist who described the random motion of microscopic pollen spores and dust). Because these clays are always in suspension, wash load is that component of the particulate or clastic load that is “washed” through the river system. Unlike coarser suspended sediment, wash load tends to be uniformly distributed throughout the water column. That is, unlike the coarser load, it does not vary with height above the bed.

Distinction is made between fully-suspended load and bed load by classifying the intermediate and transient transport state as saltation load transport. These are particles that bounce along the channel, partly supported by the turbulence in the flow and partly by the bed. They follow a distinctively asymmetric trajectory. Saltation load may be measured as suspended load (when in the water column) or as bedload (when on the bed). Although the distinction between saltation load and other types of sediment load may be important to those studying the physics of grain movement, most geomorphologists are content to ignore it as a special case.
ore uniform grain-size profile.


Bed load
^^^^^^^^^^^^^^^^^^^^^^^^^^

**Bed load** is the clastic (particulate) material that moves through the channel fully supported by the channel bed itself. These materials, mainly sand and gravel, are kept in motion (rolling and sliding) by the shear stress acting at the boundary. Unlike the suspended load, the bed-load component is almost always capacity limited (that is, a function of hydraulics rather than supply). A distinction is often made between the bed-material load and the bed load.

**Bed-material load** is that part of the sediment load found in appreciable quantities in the bed (generally > 0.062 mm in diameter) and is collected in a bed-load sampler. That is, the bed material is the source of this load component and it includes particles that slide and roll along the bed (in bed-load transport) but also those near the bed transported in saltation or suspension. Bed load, strictly defined, is just that component of the moving sediment that is supported by the bed (and not by the flow).

Theory of sediment entrainment
*******************************

.. figure:: images/liftdrag.png
   :scale: 47 %
   :alt: Lift & drag forces acting on a submerged particle.
   :align: center

   Lift & drag forces acting on a submerged particle.


At a very simple deterministic level of analysis, a particle of sediment will begin to move when the force of the flowing water applied to it equals its submerged weight. This simple analysis leads to:


.. math::

   \tau_{cr} = K g (\rho_s - \rho) D

where :math:`K = \eta /\tan(\phi)` and :math:`\eta = n D^2` (a packing coefficient) and :math:`\phi` is the internal angle of friction of the sediment.

Although this simple analytical approach (called the White analysis, after its originator) is useful because it highlights the general structural relationships (balance of forces) involved in this problem, it is not of much practical use because it greatly oversimplifies the actual complex forces involved. That is, there is more to this problem of specifying the entrainment conditions than merely balancing mean boundary shear stress and the submerged weight of the particle. Mean boundary shear stress is just one of several impelling forces and the particle submerged weight is just one of several inertial forces. Unfortunately, the other forces are very difficult to characterise in a precise quantitative.

The most widely used semi-empirical approach to defining the threshold of sediment motion was proposed in the early 1900’s by the German physicist Albert F. Shields. Shields (1936) plotted the dimensionless shear stress (:math:`\theta = \tau_{cr} / (g(\rho_s - \rho)D)`) against the particle Reynolds number (:math:`Re_p = D / \delta_0`) where :math:`\delta_0` is the thickness of the laminar sublayer.

The dimensionless shear stress in the Shields diagram is commonly termed the Shields stress or the Shields parameter. Several aspects of the Shields diagram are particularly noteworthy:

.. figure:: images/shield.png
   :scale: 65 %
   :alt: Shields Diagram from Van Rijn (1984).
   :align: center

   Shields Diagram from Van Rijn (1984).


1. The lowest Shields stress occurs in the sand range (0.06-2.00 mm). Sand is small enough to have small mass but too large for adhesion forces to come into play.
2. Silt/clay, in spite of the smaller size, requires a higher shear stress for motion than sand. Here adhesion forces become overwhelmingly large and bind the sediment together into a mass that is very resistant to erosion.
3. The Shields parameter for gravel is constant at 0.06, implying that Shields stress here becomes a simple function of grain size. This is a quite remarkable finding and allows us, as we will see below, to derive a simple relationship between the size of gravel and the shear stress required to move it.
4. The Shields parameter applies well to natural gravel-bed rivers.
