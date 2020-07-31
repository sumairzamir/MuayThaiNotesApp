[ Add image ]

# :boxing_glove: MuayThaiNotes
MuayThaiNotes is a :boxing_glove: logging app built to help beginners and technicians keep track of their combinations and improve the effectiveness of training sessions. 

Download the latest version of the app from the App Store:


The Android version is coming soon!

# Built using
- Swift 5.3x
- UIKit
- RealmSwift
- Programmatic layout construction (built using UIKit)
- Local data persistance (Realm)
- MVVM (Model - View - ViewModel) architecture
- Property wrappers
- Extension classes (UIKit)


Technical specifications & learning:
- Fully programmatic layout construction (subclassing UIView, autolayout)
- Working data model (to be migrated to offline database, e.g. Realm)
- MVVM architecture implementation
- Property wrappers (inc. generics)
- Custom extension classes
- Custom enum for constants
- Instance management
- Array functions (map, compactmap, index, mirror)
- Optional handling (guard, if let)
- Animations (alpha, fade, hidden)

Terms: 
- Workout: Refers to the daily training session. A user can save multiple combinations to a workout (inc. duplication)
- Saved combinations: Refers to combinations saved. These are frequently used combinations and are unique. For quick selection

Features:
- Select a date for your workout
- Save combinations for daily workouts from a selection screen
- Save unique combinations for quick selection in your workout
- Reorganise combinations both in workouts and saved combinations (drag & drop)
- Save combinations from the workout (drag left)
- Delete combinations (drag left)

Views:
- Workout: Presents combinations logged for a specific date
- Saved combinations: Presents unique combinations saved for quick selection
- Add combinations: Presents the ability to select a new combination and select a saved combination
- New combination: Select a new combination. Strikes split between offence and defence
- Key: Information about the strikes, labelled and colour scheme

Device support:
- iPhone and iPad
- Optimised for all screen sizes from iPhone SE (1st gen) to iPhone 11 XS Max. All iPad models with iOS 13+ support.
