---
name: Cocoa Xu
pic_url: "/assets/images/cocoa-xu.jpg"
tagline: A UwU Software Engineer
github: cocoa-xu
twitter: _uwu_cocoa

---
Cocoa is a software engineer, and there was a time when they needed to do some image-processing tasks in Elixir, but there were no Elixir libraries that could satisfy their demands. So Cocoa developed this Evision library to address image-processing tasks in Elixir using OpenCV.  
  
Previously, there were mainly two ways to use OpenCV in Elixir: creating a helper process (written in C++, Python or other languages) and communicating through a pipe, or manually porting OpenCV functions as NIFs, native-implemented functions so that Erlang and Elixir can load and use them directly.  
  
These two approaches have different pros and cons, and this library focuses on the latter and tries to automate the whole porting process. later received 1-year funding from the Erlang Ecosystem Foundation.