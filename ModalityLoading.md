# Modality Loading

## Overview
The `ModalityLoadingPopUp` is a utility object designed to display a modal loading dialog. This component is essential for providing feedback to the user during long-running, asynchronous operations such as network requests or data processing. It blocks interaction with the underlying UI, ensuring the user waits for the task to complete.

The dialog consists of a circular progress indicator and a customizable title, clearly communicating that a process is underway.

## Key Features
- **Blocks UI Interaction**: Prevents user interaction with the app while a background task is running.
- **Clear Visual Feedback**: Uses a `CircularProgressIndicator` and a text label to inform the user of an active process.
- **Simple API**: A single static method, `ModalityLoadingPopUp.show()`, makes it extremely easy to implement.
- **Programmatic Control**: The `show()` method returns the `AlertDialog` instance, allowing you to dismiss the dialog programmatically when the task is finished.
- **Customizable Title**: The loading message can be customized to provide context for the operation being performed.
- **Cancelable Action**: Provides an option to control whether the user can dismiss the dialog using the back button or by tapping outside.

---

## Kotlin Implementation
The primary method for displaying the loading dialog is through the `ModalityLoadingPopUp` object.

