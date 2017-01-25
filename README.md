## Inventory Tracking Application ##
This android application was created with the purpose of tracking inventory or equipment.
This is the source code of the app developed in Android Studio, along with a standalone APK of the app.

Use cases:
* Users must create (or login) into an account.
* Create a project with other members and a leader.
* Add equipment with a barcode to a database.
* Equipment can be assigned to a project or an individual with a selected due date.
* View all other indivduals, projects and equipment.
* Equipment can be marked as damaged and/or be returned.
* All the information from the database is then shown in various user-specified clear lists. Such as 'Objects assigned to a specified project'.
* The database is hosted online to enable use across devices by different users.

The app is currently deployed on the [Play Store.](https://play.google.com/store/apps/details?id=sweng.aa03.inventorytracking)

To scan barcodes the Google Mobile Vision API was used. It supports all common barcode formats including 2D barcodes. Documentation can be found [here.](https://developers.google.com/vision/barcodes-overview)

To host the database we used Firebase, a realtime cloud-hosted NoSQL database. We stored the data in JSON format. 

Contributers:
Seán Durban,
 Luke Egan,
 Ben Stratford,
 Nicky Casey,
 Gavin Corkery,
 Seamus Dwyer




