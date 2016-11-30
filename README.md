# An In-Depth Study of the MVVM Light Databinding System

My code samples for the Xamarin Evolve 2016 conference (Orlando FL)

# Presentation details, Slides, Video

You can see the video recording and the slides here:

http://galasoft.ch/presentations/presentationdetails.cshtml?name=2016006

# Abstract

Living in the dark ages and still wiring up properties manually between your user interface and data source? Databinding is a technique to automatically synchronize a user interface with it's data source and can vastly simplify how your app displays and interacts with data. While databinding is available out of the box for Xamarin.Forms and Windows applications, additional components are needed in Xamarin.Android and Xamarin.iOS. In this session, learn how to leverage databinding in your cross-platform applications as you master MVVM Light databinding and the MVVM pattern.

# Content

## XamBindingSample

Contains binding samples for iOS, Android and Windows

- Simple binding VM -> UI element
- Simple binding UI element -> UI element with default event handling
- Simple binding UI element -> UI element with custom event handling
- Twoway binding with default conversion
- Twoway binding with custom conversion
- Using WhenSourceChanges
- Saving bindings
- Using TargetNullValue and FallbackValue
- Avoiding linker issues

Contains Commanding sample for iOS, Android, Windows

- Simple command with default event handling
- Command with custom event handling
- Command with static parameter
- Command with dynamic parameter (binding)
- Avoiding linker issues

Contains List sample for Android and Windows

- RecyclerView
- Binding to ObservableCollection
- Use the SelectedItem
- Add and remove elements from collection
- Binding between list cell UI element and data item
- Changing UI element appearance on click

## ObservableListApple 

Contains List sample for iOS

- RecyclerView
- Binding to ObservableCollection
- Use the SelectedItem
- Add and remove elements from collection
- Binding between list cell UI element and data item
- Changing UI element appearance on click
