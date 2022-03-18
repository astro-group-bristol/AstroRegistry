# AstroRegistry

Julia (Local) Registry for astrophysics packages.

To add the Astro Group Bristol registry to your Julia environment, use the following:

```
(@1.7) julia>] activate .
(DevEnv) pkg> registry add https://github.com/astro-group-bristol/AstroRegistry
```

You can now install the dependencies we need just as you would any other package, e.g.,

```
(DevEnv) pkg> add GeodesicRendering CarterBoyerLindquist
```
