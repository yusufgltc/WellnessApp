# WellnessApp
State in Jetpack Compose

**State** 
`State` is a fundamental concept that determines which UI elements to display on the screen. Compose uses `State<T>` API to automatically track state, 
making your UI reactive and capable of updating in response to state changes.

**State Hoisting** 
`State hoisting` is a design pattern where the state is "hoisted" or lifted up to the celler of the composable, making the composable stateless.

**Stateful and Stateless:**
`Statefull` These composable own a piece of state that can change over time.
`Stateless` These compasables do not hold or define or modify new state.

**Remember and RememberSaveable APIS**
`remember` is a function that allows you to remmeber a value across recomposition.
`rememberSaveable` is a function that similar to `remember`, but it also preserves the values across configuration changes, like screen rotations.

**ViewModel** 
You can use `ViewModel` with compose to handle more complex state management. `ViewModel` can hold and manage UI-related data in lifecycle-concious way, 
allowing data to survive configuration changes like screen rotations or change dark/ligth mode states.
