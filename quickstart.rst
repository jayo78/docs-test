Quickstart
==========

Start a Bento server
--------------------

#. Clone the Bento repository::

    git clone https://github.com/breakerspace/bento.git

#. Create directories for session and function data::

    cd bento/bento/server
    mkdir functions
    mkdir sessions

#. (optional) Edit runserver.py for host and port config

#. (optional) Edit core/session_mngr for execution config

#. Start the server::

    python3.6 runserver.py


Connecting as a client
----------------------
To store, execute and interact with a Bento function use the client api :file:`bento/client/api.py`. 
See testing/ for examples of api use. The interactive client can also be used :file:`experiments/interactive_client.py` 
to send requests to a Bento server on the command line.    

Run a test::

    cd testing/
    python3.6 test_hello_world.py <host> <port>

