# learn_serialization

In this project i just trying to use serialization.

## What i do here

This project i have to models User and Adress, in User class there are an attribut called adress, So what we need to do is generate User.fromJson, Adress.toJson and toJson for each model using the magic json_serializable and build_runner.

## Why serialization
This is a good approach for complex applications where classes and dart object can have too many properties to handle code manually. and using Json Serializable, Build Runner & Flutter Annotation package to auto generate code to easily convert Json Data to Dart Classes.

## How to use
just run this command :
    $ flutter pub run build_runner build

### Note
there are no UI in the project just a Scaffold and hello text in the center.
