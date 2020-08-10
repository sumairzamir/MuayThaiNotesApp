[ Add image ]

# :boxing_glove: MuayThaiNotes
MuayThaiNotes is a :boxing_glove: logging app built to help beginners and technicians keep track of their combinations, improve the effectiveness of training sessions and provide the ability to start a timer for a workout.

Download the latest version of the app from the App Store: [Add link]

The Android version is coming soon!

# Built using
- Swift 5.3x
- UIKit
- RealmSwift (local persistance)
- Firebase (Firestore)
- Toast_Swift
- Repeat
- NVActivityIndicatorView

# Technical learning
- Fully programmatic layout construction
- Local data persistance (Realm)
- MVVM (Model - View - ViewModel) architecture
- Property wrappers
- TraitCollection management
- Array functions (map, compactmap, index, mirror)

Terms: 
- Workout: Refers to the daily training session. A user can save multiple combinations to a workout (inc. duplication)
- Saved combinations: Refers to combinations saved. These are frequently used combinations and are unique. For quick selection

Features:
- Select a date for your workout
- Save combinations for daily workouts from a selection screen
- Save unique combinations for quick selection in your workout
- Start a timer for your workout, select both a round and rest timer
- Reorganise combinations both in workouts and saved combinations (drag & drop)
- Save combinations from the workout (drag left)
- Delete combinations (drag left)

Views:
- Workout: Presents combinations logged for a specific date
- Saved combinations: Presents unique combinations saved for quick selection
- Add combinations: Presents the ability to select a new combination and select a saved combination
- New combination: Select a new combination. Strikes split between offence and defence
- Key: Information about the strikes, labelled and colour scheme
- Timer: Provides user the ability to start a timer and specify round and rest duration

Device support:
- Optimised for all iPhones and iPads with iOS 13+ support
