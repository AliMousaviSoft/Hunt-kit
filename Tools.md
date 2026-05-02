

### gowaybackgo
```bash
go install -v github.com/OoS-MaMaD/gowaybackgo@latest
```


### httpx
```bash
go install -v github.com/projectdiscovery/httpx/cmd/httpx@latest
```


### FFUF
```bash
go install github.com/ffuf/ffuf/v2@latest
```


### dnsx
```bash
go install -v github.com/projectdiscovery/dnsx/cmd/dnsx@latest
```


### X8
```bash
git clone https://github.com/sh1yo/x8
cd x8
cargo build --release
# move the binary to $PATH so you can use it without specifying the full path
cp ./target/release/x8 /usr/local/bin 
# if it says that /usr/local/bin doesn't exists you can try
# sudo cp ./target/release/x8 /usr/bin
```


### subfinder
```
go install -v github.com/projectdiscovery/subfinder/v2/cmd/subfinder@latest
```