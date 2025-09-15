1. Create a New App
  Go to Setup → App Manager → New Lightning App.
  Named the app: Employee Recognition & Rewards Tracker.
2. Create Custom Objects
    Employee (to store employee details)
    Fields: Employee Name, Email, Department (Picklist), Manager (Lookup to Employee).
  Recognition (to track achievements)
    Fields: Title, Description, Date, Reward Points (Number).
    Lookup to Employee for linking recognitions.
3. Create Custom Fields
  Added fields under each object based on requirements.
  On Employee, created a Roll-Up Summary: Total Reward Points = SUM of Reward Points from related Recognitions.
4. Create Tabs
  Created Employee Tab.
  Created Recognition Tab.
