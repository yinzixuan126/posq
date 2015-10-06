# posq
POSQ is an efficient Extend or Steer function for sampling based motion planners.

All the propertiers are described in the IROS 2014 paper "A Novel RRT Extend Function for Efficient and Smooth Mobile Robot Motion Planning". 

The steer function can be used to generate closed-loop forward simulations or to control a real robot. We extend the control law of an existing discontinuous state feedback controller to make it usable as an RRT extend function and prove that all relevant stability properties are retained. We study the properties of the new approach as extender for RRT and RRT* and compare it systematically to a spline-based approach and a large and small set of motion primitives. The results show that our approach generally produces smoother paths to the goal in less time with smaller trees. For RRT*, the approach produces also the shortest paths and achieves the lowest cost solutions when given more planning time
