```toml
[dependencies]
win-msg-name = "0.1"
```

```rust
use win_msg_name::win_msg_name;

fn main() {
    println!("{}", win_msg_name(0x000f));
}
```

```
WM_PAINT
```