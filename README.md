# Ride-Sharing-Simulation

The simulation consists of four key entities: Riders, drivers, the dispatcher, and the monitor. Riders request rides from their current location to a destination. Drivers drive to pickup and drop o riders. The dispatcher
receives and satises requests from drivers for a rider, and from riders for a driver. The monitor keeps track of activities in the simulation, and when asked, generates a report of what happened during the simulation.

When a rider requests a driver, the dispatcher tries to assign a driver to the rider. If there is no driver available, the dispatcher keeps track of the rider request, waiting for a driver to become available. A rider will cancel their request if they have to wait too long for a pick up.
When a driver requests a rider, the dispatcher assigns a waiting rider, if any. If this is the driver's rst request, the dispatcher registers the driver in its 
eet. Once registered, a driver never unregisters.

## Copyright and License
Starter Code is provided by University of Toronto Computer Science Department.
Other code is written by Christina Deng and Junkang Zhang,