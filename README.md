# RaylibJsonSerialization
Header file to serialize Raylib structs to/from Json using nlohmann::json
It includes every Raylib struct as of Raylib 3.0.0, except those that are loaded from files such as Font, Image, Texture and Model because it doesn't really make sense to save these in Json format when they already have their own supported file formats.
