# MAE-384-Group-Project
The purpose of this code is to model the spread of infectious diseases using the SIR model(Susceptible-Infected-Recovered). This code provides numerical methods that involve integration, interpolation, parameter, estimation, and frequency analysis to provide an insight on the dynamics of epidemics which may be used for public health services. 

**Part 1 SIR Model Simulation**
This portion involves implementing the SIR model through the 4th order Runge-Kutta method. This provides insights on the disease provided the transmission and recovery rates of said disease.
By using this model, the user can identify how parameter varaitions affect the spread and control of diseases and it demonstrates the importance of intervention strategies to reduce infection peaks.

**Part II Interpolation**
This part of the code recovers mising data point for time steps using linear and quadratic methods. By comparing the values that were interpolated to model data, it evaluates the accuracy of each interpolation technique. 
When using this code, it will provide insight on the trade-off between data resolution and computational efficiency, which demonstrates the accuracy limits of interpolation in changing systems, such as a SIR model. 


**Part III Least Squares Estimation**
This section applies the linear least squares fitting to estimate the initial conditions and model the transmission rate and initial infected population using simplified linearized equations. With the results, it is compared across datasets with different lenghts to determine the reliability of parameter estimation. 
When implementing this code , it will show how parameter estimation improves when using longer observation periods and it evaluates the effectiveness of generalized assumptions in real world modeling. 

**Part IV Fourier Analysis**
The last part of the section is the use of the frequency domain. This explores how periodic variations in transmission rates affect how the disease spreads. By transforming time series data into the frequency domain, it identifies key frequencies and their physical interpretations. 
By using this frequency domain, it reveals the role of periodic behaviors, daily and weekly cycles, in disease spread. This also provides a basis for predicting and mitigating periodic spikes in infection rates.

**Implications**
By using these models, the public health service department can model diseases and produce prevention tactices when given a condensed city. This could help for scenario testing, policy planning, impact analysis, epidemiological forecasting, and the design of effective prevention tactics. 

**Implementation**
Each segment should be used in MATLAB
Part I: Modify initial conditions and parameters (S0,I0,R0,Beta,Gamma and T). Customize the time step h to suit the resolution
Part II: Input data timesteps with corresponding S(t), I(t), and R(t) values. Choose linear or quadratic methods based on accuracy needs.
Part III: Provide observed data(time series of infected I(t)) and initial conditions. Adjust the code to estimate parameters and update S0 and N to reflect user's population size and disease dynamics. 
Part IV: Input custom periodic variations for daily or weekly cycles. Run the code on outputs of S(t), I(t), and R(t). Adjust the frequency vector and sampling rate to match user's data resolution. 

Each segment can be used independently or combined into a comprehensive model.

**Contributors**
Josh Dearlove,
Havenly Lopez,
Elijah Paz,
Evan Schlueter
