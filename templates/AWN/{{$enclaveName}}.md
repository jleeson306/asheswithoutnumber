```varinote
enclaveName::Enclave Name
enclavePower|slider::Power|1,5,1,1
enclaveFeatures::Signifigant Features
enclaveProblems::Signifigant Problems (problem level)
enclaveTrouble|slider::Trouble (Sum of problem levels)|1,10,1,1
enclaveGoal::Enclave Current Goal
```
Power: {{$enclavePower}}
Cohesion: {{\$enclavePower}}
Trouble: {{$enclaveTrouble}}
- **Features:** {{$enclaveFeatures}}
- **Problems:** {{$enclaveProblems}}
- **Goal:** {{$enclaveGoal}}