<div align="right">
<img src="/images/Logo_istituzionale.png" alt="drawing" width="250"/>
</div>


# Rotating turbine machinery

Rotating turbine machinery is by far the most dominant form of hydroelectric technology. Beyond hydropower applications, turbines are involved in the production of more than 90% of the world’s energy, spanning hydroelectric, thermal, nuclear, and wind power plants. The remaining share is primarily covered by photovoltaics and other emerging or minor technologies.

The H-Hope project is focused on vortex induced vibration, but for the sake of comparison and integration into sections on **Raising the clean energy transition CET narrative and Broadening knowledge and experience on operation of water turbine machinery and hidden hydropower**, information on rotating turbine machinery is provided. Also, Efficiency of the rotating turbine machinery, a comparison of efficiency among the two is provided. This may help to the understanding of operation of VIV energy harvesters also.

### **Power and torque**

From high school physics, we know that torque *M* and angular frequency *ω* are related to power *P* by a well-established relationship.

$$
P = M \cdot \omega \quad \text{(Eq. 1)}
$$

We now aim to relate the flow within the turbine machinery to its power and torque. From physics, we know that the net torque on a body equals the rate of change of its angular momentum *L*. In turbine machinery, we connect the change in angular momentum—associated with the flow velocity *v* to the shaft torque *M* For simplicity, we omit vector notation in the following discussion.

$$
M = \frac{dL}{dt} = \frac{d(mrv)}{dt} \quad \text{(Eq. 2)}
$$

and

$$
P = \omega \cdot \frac{dL}{dt} = \omega \cdot \frac{d(mrv)}{dt} \quad \text{(Eq. 3)}
$$

In the turbine, a change in the fluid's angular momentum (time derivative) within the runner directly results in a useful net torque on the runner shaft. Due to the conservation of mass (continuity), the fluid velocity in the meridional (axial) direction cannot change significantly. Therefore, any necessary changes in the flow velocity, according to the relationship discussed above, must occur primarily in the tangential direction. The tangential velocity of the runner u is related to the rotor's angular frequency and its radius.

$$
u = \omega r \quad \text{(Eq. 4)}
$$

The change in mass over a given time interval corresponds to the mass flow rate. Using the velocity notation introduced earlier, the Equation 4 can be rewritten accordingly. We consider the difference between the turbine inlet (index 1) and outlet (index 2) conditions:

$$
P_{shaft} = \omega \cdot \dot{m} (r_1 c_{u1} - r_2 c_{u2}) \quad \text{(Eq. 5)}
$$

The Equation 5 for the shaft power can be written instead of with angular velocity *ω* using the tangential velocity of the runner *u*<sub>1</sub> and *u*<sub>2</sub>

$$
P_{shaft} = \dot{m} (u_1 c_{u1} - u_2 c_{u2}) \quad \text{(Eq. 6)}
$$

In the above two Equations 5 and 6, projection of the absolute velocity *c* onto circumferential velocity *u* (also called swirling velocity) is *c*<sub>u1</sub> for the inlet and *c*<sub>u2</sub> for the outlet. The Equation  6 above is called the **Euler equation of the turbine machinery**. From the Euler equation, we recognise the following:
 - rotor must rotate to produce useful energy,
 - the more swirl the rotor gets from the fluid, the more energy transfer we have,
 - for large energy transfer, it is useful to change radius (centrifugal machinery, high radius at the inlet, and smaller at the outlet).

### **Energy transfer in rotating machinery – axial turbine**
Now that we have provided the fundamental equations necessary for understanding the operation of rotating turbines, we can explain the working principle of an axial turbine. We consider an axial water turbine designed, for example, to be installed within a water supply network pipe. The pipe diameter upstream, inside, and downstream of the turbine remains constant, meaning that the fluid velocity in the axial direction does not change significantly throughout the turbine. A sample small axial turbine configuration for installation in a pipe is shown in Figure 1 below.
The incoming flow enters the turbine from the left. The first component of the axial turbine is the guide vane (shown in blue). The guide vane is positioned at an angle to the axial flow and imparts a tangential component to the incoming water velocity. As a result, a portion of the total incoming energy—which initially consists of both pressure energy and axial kinetic energy—is converted into tangential kinetic energy, denoted by *c*<sub>u1</sub>. According to Bernoulli’s equation (Equation 1), this increase in tangential velocity must be accompanied by a decrease in pressure. Due to the induced tangential velocity, the flow now possesses the angular momentum *𝐿* upon entering the runner. The runner (depicted in green) interacts with this swirling flow, working to reduce the tangential velocity back to zero. Through this process, and according to Equation 2, a torque *𝑀* is generated on the runner shaft. Ideally, the flow exits the runner with zero tangential velocity *c*<sub>u2</sub> =0, having transferred all of its tangential kinetic energy to the runner, and subsequently to the induction generator. Because energy is transferred to the runner and induction generator primarily through velocity in rotating turbine machinery, energy losses are minimal.

<div align="center">
<img src="/images/Picture1.png" alt="drawing" width="700"/>
</div>
Figure 1: A 180° cut-out view of the axial turbine example. The guide vane is shown in blue, the runner in green, and the structural supports in yellow. The induction generator, located downstream, is not depicted for clarity. Red and light blue indicate caps at the hub, which help guide the flow and prevent flow separation near the central axis.

### **Efficiency of the rotating turbine machinery** 

A key difference between vortex-induced vibration (VIV) energy harvesters and rotating turbine machinery lies in the mechanism of energy conversion. In VIV harvesters, the energy of the incoming water flow is reduced and transferred into structural motion through a cascade of turbulent energy decay. This results in fluctuating forces acting on the cylinder. Moreover, VIV energy harvesting systems are constrained by an efficiency limit analogous to the Betz limit, which caps the proportion of flow energy that can be extracted.

In contrast, rotating turbine machinery utilizes the pressure upstream of the turbine, converting it into kinetic energy (specifically tangential velocity and angular momentum), which is then efficiently transferred to the runner and subsequently to the induction generator. Because this process does not involve extracting energy by decelerating the flow as in VIV systems, limits like the Betz limit do not apply. As a result, rotating turbine systems can achieve very high efficiencies—exceeding 95% in very large-scale machines.


&nbsp;

<div align="center">
<img src="./images/H-HOPE_footer.JPG" alt="drawing" width="1472"/>
</div>
