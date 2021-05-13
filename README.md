# rust-utils
A collection of Rust scripts, mainly ones I get tired of rewriting and/or debugging and researching.
 
# Table of Contents
## [rocket-spa-routing.rs](https://github.com/drannex42/rust-utils/blob/main/rocket-spa-routing.rs)
This is a simple 'hack' to use Rocket's own 404 page daemon to load your SPA for proper routing. If your SPA uses '/something' then you should be able to navigate directly there through your browser and not get the Rocket 404 page. This is a way to do that.
