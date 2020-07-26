# MuayThaiNotesApp

Purpose: An app to log the combinations used as part of your Muay Thai training sessions

Problem: As a user I would like to log my combinations so that I can recall my training sessions for future use

Target: New & experienced Muay Thai technicians

Technical specifications & learning:
- Fully programmatic layout construction (subclassing UIView)
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
