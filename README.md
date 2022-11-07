# Messiah MPK Decrypt Tool

Tool to decrypt MPK files as they are used in NetEase's Messiah Engine.

## Building

All you have to do to build it is clone it an run on of the following:

```
cargo build --release
```
or to install
```
cargo install --path .
```

## Usage

Example:

```
messiah-mpk <mpkinfo> <path to save>
```

## Supported File Types

- [x] **MPK Archives** [messiah-mpk](mpk)
- [x] **Resource Repositories** [messiah-resources](resources)
- [x] **Python Scripts** [messiah-pyc](pyc)
- [x] **Textures** *(partially)* [messiah-texture](texture)
- [ ] **Models**
- [ ] **Animations**
- [ ] **Sounds**
- [ ] **Material**
