# ScreenBrodcast
Distributed System Mini-Project-Assignment WKU Department  Of Computer Science

/**
 * This class is used to transfer data between client and server.
 * The application stabilish a protocol with these commands/parameters.
 * 
 * +--------------+---------------------------------------------------+
 * | command      | behavior                                          |
 * +--------------+---------------------------------------------------+
 * | connect      | client requests to connect on server.             |
 * +--------------+---------------------------------------------------+
 * | connected    | server accepts the connection requested and       |
 * |              | informs the client.                               |
 * +--------------+---------------------------------------------------+
 * | disconnect   | client requests to disconnect from server.        |
 * +--------------+---------------------------------------------------+
 * | disconnected | server disconnects a client.                      |
 * +--------------+---------------------------------------------------+
 * | data Transfer | server sends data to client (after a successfull  |
 * |              | connection).                                      |
 * +--------------+---------------------------------------------------+
 * 
