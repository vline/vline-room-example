# vLine Room Example

This is a simple example that demonstrates how to create a "room" with the vLine API. When a user joins the "room",
they automatically start calling the other user and the remote end automatically accepts the call. If the remote user
 is not in the room when the first user joins, it will wait to connect until the user joins.

## Testing Locally

* Read the comments in the `source/index.html` file and replace the global (capitalized) variables with appropriate
values.
* Run the `server.sh` script.
* Go to [http://localhost:4567](http://localhost:4567) in your browser.

## Deploying

Your server should generate and inject appropriate values for the global (capitalized) variables. Take a look at the
other [vLine Examples](https://github.com/vline), such as as the [Rails example](https://github.com/vline/vline-rails-example),
to see how to do this.