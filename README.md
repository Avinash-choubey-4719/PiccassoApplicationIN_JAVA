# PiccassoApplicationIN_JAVA

Images add much-needed context and visual flair to Android applications. Picasso allows for hassle-free image loading in your application—often in one line of code!

Picasso.get().load("https://i.imgur.com/DvpvklR.png").into(imageView);
Many common pitfalls of image loading on Android are handled automatically by Picasso:

Handling ImageView recycling and download cancelation in an adapter.
Complex image transformations with minimal memory use.
Automatic memory and disk caching.


MAVEN
<dependency>
  <groupId>com.squareup.picasso3</groupId>
  <artifactId>picasso</artifactId>
  <version>(insert latest version)</version>
</dependency>
GRADLE
implementation 'com.squareup.picasso:picasso:(insert latest version)'
