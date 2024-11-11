### What is this?

* Rails demo app 
* re: how to set up [pagy](https://github.com/ddnexus/pagy).
* with keyset pagination + infinite scrolling.

Please check out other [pagy demo apps](https://github.com/stars/benkoshy/lists/rails-demo-apps-for-pagy) if you want to see samples of how other functionality can be set up.

* Rails: 8.0.0
* Ruby: +3.2.0

### Commit Summary

* Check out a summary of the set up instructions on commit [12b0e25](https://github.com/benkoshy/pagy_keyset_infinite/commit/12b0e25f704f41d4051837bbda08ae9ae4a7aae3)
* Details of the frames / turbo_streams required can be found here: https://github.com/benkoshy/pagy_keyset_infinite/commit/88e54fdf953fc4a0b0f591e24cc974364d289ef7

### Set up Instructions

```sh
rake db:migrate db:seed 
```

The following sets up the database, and "seeds" it - i.e. filling it with 1000s records.


```sh
./bin/dev
# starts the rails server
```

Point your browser to: [http://[::1]:3000](http://[::1]:3000) and you should see pagy functioning.

### License

MIT

### Contributing

* If I've made a mistake, or this app needs updating - please feel free to raise an issue. 

* PRs fixing bugs will be welcomed!


### Infinite Pagination via Keyset

Credit: https://youtu.be/bVvLNpJyZuw



