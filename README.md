# Farcon

FarmConnect is a Flutter application that connects farmers directly with customers, offering farm-fresh vegetables and milk at competitive prices. This project uses MongoDB Atlas for storing data and Cloudinary for storing images. The frontend is built with Flutter, and the backend is created using Express.js and Node.js.

## Getting Started

This project is a starting point for a Flutter application.

### Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed [Flutter](https://docs.flutter.dev/get-started/install) on your machine.
- You have a MongoDB Atlas account and have created a cluster.
- You have a Cloudinary account for storing images.

### Installation

1. Clone the repo:
   ```sh
   git clone https://github.com/shivprasadrahulwad/farcon.git
   cd farcon

2. Install Flutter dependencies:
   flutter pub get

3. Create account 
   - You have a MongoDB Atlas account and have created a cluster.
   - You have a Cloudinary account for storing images.

4. Add cluster link 
   DB = "<your cluster link>"

5. Open index.js in terminal and run the following command
   nodemon ./index.js

# Configuration
 
 dependencies:
  flutter:
    sdk: flutter


  # The following adds the Cupertino Icons font to your application.
  # Use with the CupertinoIcons class for iOS style icons.
  cupertino_icons: ^1.0.2
  http: ^1.1.0
  provider: ^6.1.2
  shared_preferences: ^2.2.1
  badges: ^3.1.2
  dotted_border: ^2.1.0
  carousel_images: ^1.1.2
  carousel_slider: ^4.2.1
  cloudinary_public: ^0.23.1
  image_network: ^2.5.4+1
  animated_splash_screen: ^1.3.0
  lottie: ^2.7.0
  flutter_polyline_points: ^2.0.0
  flutter_svg: ^2.0.10+1
  flutter_local_notifications: ^17.1.0
  share_plus: ^7.2.2
  path_provider: ^2.1.3
  intl: ^0.19.0
  fl_chart: ^0.60.0
  numberpicker: ^2.1.2
  percent_indicator: ^4.2.3
  moment_dart: ^2.1.0
  flutter_launcher_icons: ^0.13.1

# Usage

1. Run the application:
   nodemon ./index.js

2. The application will connect to MongoDB Atlas for data storage and use Cloudinary for image storage


# Built With
Flutter - The mobile framework used
MongoDB Atlas - Database for storing application data
Cloudinary - Image storage solution



# License
Distributed under the MIT License. See LICENSE for more information.


# Acknowledgments
  -https://www.mongodb.com/
  -[Flutter Dotenv](https://pub.dev/packages/flutter_dotenv)
  -https://cloudinary.com/


# Resources
A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.