# DNS Benchmarking Tools


* [DNSBench](#dnsbench)
* [namebench](#namebench)


## [DNSBench](https://www.grc.com/dns/benchmark.htm)
* Gibson Research Corporation

GRC's DNS Benchmark performs a detailed analysis and comparison of the operational performance and reliability of any set of up to 200 DNS nameservers (sometimes also called resolvers) at once. When the Benchmark is started in its default configuration, it identifies all DNS nameservers the user's system is currently configured to use and adds them to its built-in list of publicly available “alternative” nameservers. Each DNS nameserver in the benchmark list is carefully “characterized” to determine its suitability — to you — for your use as a DNS resolver. This characterization includes testing each nameserver for its “redirection” behavior: whether it returns an error for a bad domain request, or redirects a user's web browser to a commercial marketing-oriented page. While such behavior may be acceptable to some users, others may find this objectionable.

The point made above about the suitability — to you — of candidate nameservers is a crucial one, since everything is about where you are located relative to the nameservers being tested. You might see someone talking about how fast some specific DNS nameservers are for them, but unless you share their location there's absolutely no guarantee that the same nameservers would perform as well for you. ONLY by benchmarking DNS resolvers from your own location, as this DNS Benchmark does, can you compare nameserver performance where it matters . . . right where you're computer is.
When the benchmark is run, the performance and apparent reliability of the DNS nameservers the system is currently using, plus all of the working nameservers on the Benchmark's built-in list of alternative nameservers are compared with each other.

Results are continuously displayed and updated while the benchmark is underway, with a dynamically sorted and scaled bar chart, and a tabular chart display showing the cached, uncached and “dotcom” DNS lookup performance of each nameserver. These values are determined by carefully querying each nameserver for the IP addresses of the top 50 most popular domain names on the Internet and also by querying for nonexistent domains.

Once the benchmark finishes, the results are heuristically and statistically analyzed to present a comprehensive yet simplified and understandable English-language summary of all important findings and conclusions. Based upon these results, users may choose to change the usage order of their system's own resolvers, or, if alternative public nameservers offer superior performance or features compared with the nameservers currently being used, to switch to one or more alternative nameservers.

## [namebench](https://code.google.com/archive/p/namebench/)
* Google

Are you a power-user with 5 minutes to spare? Do you want a faster internet experience?  

Try out namebench. It hunts down the fastest [DNS](http://en.wikipedia.org/wiki/Domain_Name_System) servers available for your computer to use. namebench runs a fair and thorough benchmark using your web browser history, tcpdump output, or standardized datasets in order to provide an individualized recommendation. namebench is completely free and does not modify your system in any way. This project began as a 20% project at Google.
