# DRK-TokenIZER
This code works for drk servers to tokenize drk code blocks in drk files 


## Usage and about


when making a drk code block you can use normal rust along with drkRS; drkRS is drk rust script which is like rust with built in web usage

The DRK tokenizer takes drkRS + Rust and converts it to rust and http

To start using DRK make 2 files one has to be named index the other what ever you want the first page if needed.

```rust
index.drk
```
along if you want to make global backend code make a files called index.drks for drk script 

In the drks file to make routes add the following 

```rust
new routes{
  "/aboutme": "mypage.drk"
};
```
you can also add global functions or code to other files with the export method

