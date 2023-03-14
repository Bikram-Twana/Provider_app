# provider_app

Understanding State Management using Provider

State is the data that determines our app's UI.
<b> State Management </b> is how we organize our app to most effectively access state and share it across widgets. i.e reflecting state changes in differnt parts of the screens. 
<br>
State Management has two goals: 
    a. provide access to data
    b. tell widgets that they need to be redrawn when the data changes.

<br>

Some State Management Approaches:
    1. Provider
    2. GetX
    3. BLOC
    4. Riverpod
<br>
<br>


<b> Provider </b> : is basically a container or a storage that stores and provides you with state or data.
It is central point to manage the state.
As we know that widgets are arranged in an app like a tree like fashion. so, if u assign Provider to any node in the tree then all the children of that node will have access to the data that is provided by the Provider.
<br>
<u>Components of Provider</u>
    i. Change Notifier : Data Holder class
    ii. ChangeNotifierProvider: Entry Point,
    iii. Consumer: User that use the data,
    iv. Provider.of<> : Interats with the data holder
