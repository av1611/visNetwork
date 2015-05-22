# WARNING

### vis.js was updated recently from 3.12.0 to 4.0, adding some functionnalities, and changing all html documentation. Let us a few weeks to update visNetwork code, options, and man !

# visNetwork
R package, using vis.js library for network visualization

```` 
devtools::install_github("dataknowledge/visNetwork")

require(visNetwork)
?visNetwork

nodes <- data.frame(id = 1:3)
edges <- data.frame(from = c(1,2), to = c(1,3))
visNetwork(nodes, edges)

````

A page of examples is under construction, and available at 
http://dataknowledge.github.io/visNetwork/
