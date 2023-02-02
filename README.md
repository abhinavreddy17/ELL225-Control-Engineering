# Quarter Car Suspension Model

The suspension system is one of the most significant components of a vehicle, as it reduces the impact loads from the road to enhance the ride comfort and **stability**. Suppose a vehicle is traversing a random surface![Image](https://user-images.githubusercontent.com/119739544/216402226-0002416a-51bd-4531-b963-8fa474108676.jpg)

, which causes the vehicle to jolt and cause discomfort for the passengers. The quantities Zs and Zu are vertical displacements in the car body and car wheel, respectively, due to displacement Zr induced by an uneven road. The quantity of interest here is $Zs-Zu$, which is the displacement seen here, and we can obtain step input responses from them. Anyway, the system responses is not good for the practical application, as we can see that it is having significant overshoot, which may cause discomfort to the passenger, so we try to optimize the system by remodeling the system by adding a compensator, that will alter the overshoot and the settling time of the step response. Ideally, we would want systems which that lower overshoot and lower settling time. And assuming here that R(s) = 0, the block diagram further simplifies as shown. And for all different compensators, the final plots are extracted. We had tried various types of compensators to the system to test the system and obtain the optimum response. The system response is the blue coloured plot as shown we had seen that this has overshoot, now we try to optimize by adding compensators. 
### Discussion
We were unable to achieve a substantial variance from the uncompensated system response for the P compensator or the PI compensator, which is practically the same plot as that of the uncompensated system response, whereas for PD if we see the overshoot and settling time vary and they both are less than that of system response which is an improvement, similarly all others were obtained as well, but the standouts are PD compensator and PID compensator, PID is also effective, although it experiences higher overshoot over a greater amount of time than PD compensator. So, by adding a compensator to the Quarter Car Suspension Model, we can make better systems, which are having lower overshoot and settling time and that are fitting well to the practical conditions.
