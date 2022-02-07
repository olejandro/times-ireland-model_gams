# TIMES-Ireland Model (TIM) in GAMS
This is a GAMS version of the [TIMES-Ireland Model (TIM)](https://github.com/MaREI-EPMG/times-ireland-model).

To obtain the model, including the TIMES source code, run the following command:
> git clone --recurse-submodules https://github.com/MaREI-EPMG/times-ireland-model_gams

To run a specific scenario (e.g. WAM) execute the following command from root:
> GAMS runmodel --scenario=WAM

The model is solved using CBC by default. Adjust the command to solve it e.g., with CPLEX:
> GAMS runmodel --scenario=WAM --solve_with=CPLEX
