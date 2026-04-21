# BadPLC

# -------------------------------------------------
# Coils / Buttons
# 00001 Drain Down 1%
# 00002 Fill Up 1%
# 00003 Idle / Stop
# 00004 Attack Enable
# 00005 Sensor Spoof
# 00006 Force Drain
# 00007 Drain to 0
# 00008 Unused
# 00009 Fill to 100
# 00010 Stop Auto Action
# 00011 Attacker Overload Simulation
# 00012 Reset Pump Fault
#
# Discrete Inputs / Pilot Lights
# 10001 Low Level
# 10002 High Level
# 10003 Tank Empty
# 10004 Tank Full
# 10005 Pump Running
# 10006 Pump Fault
# 10007 Pump Overload
#
# Holding Registers / Displays
# 40001 Real Tank Level
# 40002 Displayed Tank Level
# 40003 Mode
#        0 = Idle
#        1 = Drain 1
#        2 = Fill 1
#        3 = Drain to 0
#        4 = Fill to 100
# 40004 Status Code
#        0 = Normal
#        1 = Sensor Spoof
#        2 = Forced Drain
#        3 = Pump Overloaded
# 40005 Pump Speed
# 40006 Pump Current
# 40007 Pump Temperature
# 40008 Pump Fault Code
#        0 = Normal
#        1 = Overload
# -------------------------------------------------
