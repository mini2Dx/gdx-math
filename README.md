# gdx-math
LibGDX math classes extracted into a standalone library (i.e. no OpenGL, LWJGL, etc. required)

## Mechanism

The gradle build will checkout a specific version of libgdx, copy the math source files into src/main/java, package renamed from _com.badlogic_ to _org.mini2Dx_ and compile the standalone jar.

## Usage

```gradle
compile "org.mini2Dx:gdx-math:1.9.5"
```

## Included Classes

The entire _com.badlogic.gdx.math_ package is included