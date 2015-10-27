not-an-http-service
===================
A [gb](http://getgb.io/)-vendored version of the [not-a-web-framework](https://github.com/oleksandr/not-a-web-framework) with minor modifications

* `gorilla/mux` as a router instead of the `github.com/julienschmidt/httprouter`

Original description:

A baseline for creating web-services in Go (a bit on steroids, but still pretty small). It's not a framework, not even a library. Steal this code instead of making yet another framework out of it! Don't even `go get` this package. Instead - git clone and merge it with your code base or build your next service on top of it.

The inspiration comes from the blog post [Build Your Own Framework in Go](http://nicolasmerouze.com/build-web-framework-golang/).