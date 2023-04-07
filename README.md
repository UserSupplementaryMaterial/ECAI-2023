# SafetyShieldsBDI

##Instrumentation

The instrument.py file contains the code for instrumenting a BDI agent implemented in Jason. To test, just run it in the terminal.
The only command line argument to pass is the name of the file to instrument (eg. radiation_agent.asl).

##JaCaMo

Inside the example folder, a JaCaMo abstract example can be found. It contains the code of the example presented in the paper (the radiation one). In more detail, it already contains the instrumented agent. In general, the pipeline would consist in running the instrumentation script on as .asl file, and then substitute the resulting file with the one in the project. We already carried out this step, so the agent in the project is already the instrumented one. To run it, it is enough to install the project through gradle and then run it.
