# Second Life implemented as a DLL (includes attention model)

Kokkinara E, Oyekoya O, Steed A. (2011). Modelling Selective Visual Attention for Autonomous Virtual Characters, Journal of Computer Animation and Virtual Worlds, CASA 2011, Chengdu, China. - http://ooyekoy.people.clemson.edu/cav425.pdf

See the section 4.5 and the source code (pp 87-104) of http://ooyekoy.people.clemson.edu/thesis/MScThesis.pdf to see how it was integrated into the Second Life source code.

Note on secondlife.dll - Attempted to get this working with OpenGL intercept application. Got the dll working but not all OpenGL calls are being intercepted. It was a fun try though. Change flag to build as executable instead and try out the attention model within second life.