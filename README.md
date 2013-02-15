erlang-server-example
=====================

A reaaally basic erlang server, for demonstration purposes only.

Based on [this post](http://stackoverflow.com/questions/2206933/how-to-write-a-simple-webserver-in-erlang).  I just wanted to see if I could make it read a file.

## Usage

    $ git clone git@github.com:wulftone/erlang-server-example.git

    $ cd erlang-server-example

    $ erl

    Erlang R15B02 (erts-5.9.2) [source] [64-bit] [smp:4:4] [async-threads:0] [hipe] [kernel-poll:false]
    Eshell V5.9.2  (abort with ^G)
    1> c(hello).
    {ok,hello}
    2> Pid = hello:start(9000).
    <0.39.0>
    3> exit(Pid,ok).
    true
