# Read: Class 41
## Intent Filters
- Allowing Other Apps to Start Your Activity
If your app can perform an action that might be useful from another app, your app should be prepared to respond to action requests by specifying the appropriate intent filter in your activity.
Then, when users initiate a «share» action from another app, your app appears as an option in the chooser dialog , To allow other apps to start your activity in this way, you need to add an element in your manifest file for the corresponding element.
When an app calls startActivity or startActivityForResult, with an implicit intent, the system finds which activity can respond to the intent.

- Add an Intent Filter
The system may send a given Intent to an activity if that activity has an intent filter fulfills the following criteria of the Intent object:

- - Action
- - Data
- - Category

Each incoming intent specifies only one action and one data type, but it's OK to declare multiple instances of the <action>, <category>, and <data> elements in each <intent-filter>.

If any two pairs of action and data are mutually exclusive in their behaviors, you should create separate intent filters to specify which actions are acceptable when paired with which data types.

For example, suppose your activity handles both text and images for both the ACTION_SEND and ACTION_SENDTO intents. In this case, you must define two separate intent filters for the two actions because a ACTION_SENDTO intent must use the data Uri to specify the recipient's address using the send or sendto URI scheme.
