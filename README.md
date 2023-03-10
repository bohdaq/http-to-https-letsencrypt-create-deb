# Create Debian .deb package for Rust Web Server
To build http-to-https-letsencrypt as Debian package, put prebuilt binary http-to-https-letsencrypt at http-to-https-letsencrypt-create-deb/usr/local/bin

> dpkg-deb --build http-to-https-letsencrypt-create-deb
> 
> mv http-to-https-letsencrypt-create-deb.deb http-to-https-letsencrypt.deb

To install package execute:
> sudo dpkg -i --force-overwrite http-to-https-letsencrypt.deb

To check installation:
> http-to-https-letsencrypt


## Community
Use GitHub discussions, issues and pull requests.

There is Rust Web Server [Discord](https://discord.gg/zaErjtr5Dm) where you can ask questions and share ideas.

Follow the [Rust code of conduct](https://www.rust-lang.org/policies/code-of-conduct).

## Donations
If you appreciate my work and want to support it, feel free to do it via [PayPal](https://www.paypal.com/donate/?hosted_button_id=7J69SYZWSP6HJ).

## Links
1. [Rust Web Server](https://github.com/bohdaq/rust-web-server)
1. [Rust TLS Server](https://github.com/bohdaq/rust-tls-server)
1. [http-to-https-letsencrypt](https://github.com/bohdaq/rust-http-to-https-letsencrypt-acme)
1. [Rust Web Framework](https://github.com/bohdaq/rust-web-framework/)
1. [Create RPM Package](https://github.com/bohdaq/rws-rpm-builder)
1. [Homebrew Formula Rust TLS Server](https://github.com/bohdaq/homebrew-rust-tls-server)
1. [Homebrew Formula Rust Web Server](https://github.com/bohdaq/homebrew-rust-web-server)

