## DarkSuite

Dark styled system elements. 

[Noctis](http://cydia.saurik.com/package/com.laughingquoll.noctis/) is a system-wide attempt at dark mode. It hooks UIView and CALayer at a high level, and intelligently changes colors. This works fairly well, and results in high compatibility.

The approach I wanted to take with these tweaks was more modular. Views are specifically targeted, and colors are changed appropriately. I decided to move these tweaks out of my [personal tweaks](https://github.com/ipadkid358/personal-tweaks) repo, however these tweaks still neglect to take into account other tweaks, and compatibility. This results in less bugs with less compatibility. For me, this is not an issue, as I write all my own tweaks
