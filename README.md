# Request Approval System using Flutter, Firebase, and Cloud Firestore

Welcome to the Request Approval System repository! This project is built using Flutter and Dart for the frontend, and Firebase with Cloud Firestore for the backend. The system provides an asynchronous approval process, allowing users to submit requests for approval and designated approvers to review, approve, or reject those requests. This versatile system can be applied to various use cases like expense reimbursement, leave requests, and more.

## Demo 

- The Request Approval System is hosted on GitHub Pages. You can access the live demo [here](https://cynthiakonar.github.io/#/).
- To see the Request Approval System in action, check out our [YouTube demo video](https://youtu.be/mb6_dcK6RAc).

## Features

- User Authentication: The system supports user authentication, ensuring that only authorized users can access and interact with the approval process.

- Request Submission: Users can submit their requests through the frontend interface. The submitted requests are stored securely in the Cloud Firestore database.

- Approvers' Workflow: Designated approvers can log in to review pending requests. They have the ability to approve or reject requests based on their discretion.

- Real-time Updates: The system leverages Firebase and Cloud Firestore to provide real-time updates on request statuses, ensuring that both users and approvers have the most up-to-date information.

- Scalable and Customizable: The architecture of this system allows for easy scalability and customization. You can adapt it to your specific requirements and integrate additional features as needed.

## Getting Started

To run the Request Approval System locally, follow these steps:

1. Clone the repository to your local machine:
   
   git clone git@github.com:cynthiakonar/approval-system.git

2. Install Flutter and Dart if you haven't already. You can find installation instructions [here](https://docs.flutter.dev/get-started/install).
   
3. Navigate to the project directory:
   
   cd approval-system
   
4. Install the required packages:
   
   flutter pub get
   
5. Configure Firebase:

   Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).

6. Run the app:

   flutter run




