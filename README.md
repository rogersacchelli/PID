# PID Controller

## Parameters

Parameters have been set manually, by experimentation.

* P component describes the proportional gain against cross track error (CTE), the higher the gain, faster it's the correction towards set point. The drawback is the overshooting on the process which might lead to instability.

* I component relates to integral gain, which is intended to correct eventual bias on the process, like measurements unacurracy or external factors, which implies the called steady state error.

* D component tries to smooth the variations in order to avoid overshooting. If the gain is too high, might avoid the process to correcly achieve the set point. If it's too low, does not help on the P component overshooting avoidance.