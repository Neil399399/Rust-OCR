# Rust-OCR
Tesseract OCR with Rust

## MAC
`Homebrew`
```sh
brew install tesseract
```

## OpenCV Bug
 `--- stderr /usr/local/include/tesseract/publictypes.h:39:1: error: unknown type name 'constexpr' ...`
 
 This is openCV bug (issues 1388)[https://github.com/opencv/opencv_contrib/issues/1388]