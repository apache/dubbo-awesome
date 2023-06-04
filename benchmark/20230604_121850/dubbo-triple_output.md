# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.087 ops/ms
# Warmup Iteration   2: 5.014 ops/ms
# Warmup Iteration   3: 8.607 ops/ms
Iteration   1: 9.048 ops/ms
Iteration   2: 9.356 ops/ms
Iteration   3: 9.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.155 ±(99.9%) 3.174 ops/ms [Average]
  (min, avg, max) = (9.048, 9.155, 9.356), stdev = 0.174
  CI (99.9%): [5.981, 12.329] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.190 ops/ms
# Warmup Iteration   2: 7.928 ops/ms
# Warmup Iteration   3: 9.250 ops/ms
Iteration   1: 9.829 ops/ms
Iteration   2: 10.053 ops/ms
Iteration   3: 9.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.668 ±(99.9%) 8.865 ops/ms [Average]
  (min, avg, max) = (9.122, 9.668, 10.053), stdev = 0.486
  CI (99.9%): [0.803, 18.533] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.168 ops/ms
# Warmup Iteration   2: 8.348 ops/ms
# Warmup Iteration   3: 8.706 ops/ms
Iteration   1: 9.089 ops/ms
Iteration   2: 8.926 ops/ms
Iteration   3: 9.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.099 ±(99.9%) 3.245 ops/ms [Average]
  (min, avg, max) = (8.926, 9.099, 9.281), stdev = 0.178
  CI (99.9%): [5.854, 12.344] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.652 ops/ms
# Warmup Iteration   2: 7.109 ops/ms
# Warmup Iteration   3: 8.042 ops/ms
Iteration   1: 7.916 ops/ms
Iteration   2: 7.835 ops/ms
Iteration   3: 8.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.996 ±(99.9%) 3.878 ops/ms [Average]
  (min, avg, max) = (7.835, 7.996, 8.237), stdev = 0.213
  CI (99.9%): [4.118, 11.874] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.672 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.694 ±(99.9%) 0.007 ms/op
Iteration   1: 3.406 ±(99.9%) 0.008 ms/op
Iteration   2: 3.483 ±(99.9%) 0.007 ms/op
Iteration   3: 3.468 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.452 ±(99.9%) 0.745 ms/op [Average]
  (min, avg, max) = (3.406, 3.452, 3.483), stdev = 0.041
  CI (99.9%): [2.708, 4.197] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.486 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.603 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.004 ms/op
Iteration   1: 3.283 ±(99.9%) 0.005 ms/op
Iteration   2: 3.278 ±(99.9%) 0.005 ms/op
Iteration   3: 3.253 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.271 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (3.253, 3.271, 3.283), stdev = 0.017
  CI (99.9%): [2.970, 3.573] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.773 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.680 ±(99.9%) 0.006 ms/op
Iteration   1: 3.426 ±(99.9%) 0.010 ms/op
Iteration   2: 3.520 ±(99.9%) 0.007 ms/op
Iteration   3: 3.507 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.484 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (3.426, 3.484, 3.520), stdev = 0.051
  CI (99.9%): [2.554, 4.414] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 12.266 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.415 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.134 ±(99.9%) 0.008 ms/op
Iteration   1: 4.005 ±(99.9%) 0.009 ms/op
Iteration   2: 4.016 ±(99.9%) 0.008 ms/op
Iteration   3: 3.822 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.947 ±(99.9%) 1.984 ms/op [Average]
  (min, avg, max) = (3.822, 3.947, 4.016), stdev = 0.109
  CI (99.9%): [1.963, 5.932] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.857 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.158 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.009 ms/op
Iteration   1: 3.348 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.559 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  19.856 ms/op
                 createUser·p0.9999: 22.901 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   2: 3.433 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.335 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  21.392 ms/op
                 createUser·p0.9999: 25.814 ms/op
                 createUser·p1.00:   26.968 ms/op

Iteration   3: 3.456 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.123 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  19.333 ms/op
                 createUser·p0.9999: 27.082 ms/op
                 createUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281268
  mean =      3.412 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10215 
    [ 2.500,  5.000) = 266057 
    [ 5.000,  7.500) = 4228 
    [ 7.500, 10.000) = 333 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.456 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.009 ms/op
Iteration   1: 3.252 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  17.695 ms/op
                 existUser·p0.9999: 22.550 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   2: 3.261 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.683 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   5.241 ms/op
                 existUser·p0.999:  15.712 ms/op
                 existUser·p0.9999: 24.320 ms/op
                 existUser·p1.00:   24.904 ms/op

Iteration   3: 3.286 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   5.761 ms/op
                 existUser·p0.999:  10.420 ms/op
                 existUser·p0.9999: 25.428 ms/op
                 existUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293549
  mean =      3.267 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19091 
    [ 2.500,  5.000) = 270270 
    [ 5.000,  7.500) = 3020 
    [ 7.500, 10.000) = 668 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 116 
    [22.500, 25.000) = 124 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.224 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     16.826 ms/op
     p(99.9900) =     24.368 ms/op
     p(99.9990) =     26.125 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.736 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.012 ms/op
Iteration   1: 3.521 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.423 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  20.649 ms/op
                 getUser·p0.9999: 26.913 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   2: 3.523 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.872 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   4.407 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  23.134 ms/op
                 getUser·p0.9999: 26.242 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 3.447 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.455 ms/op
                 getUser·p0.999:  10.358 ms/op
                 getUser·p0.9999: 25.943 ms/op
                 getUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274398
  mean =      3.497 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9937 
    [ 2.500,  5.000) = 254776 
    [ 5.000,  7.500) = 8286 
    [ 7.500, 10.000) = 992 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 99 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.994 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     26.528 ms/op
     p(99.9990) =     27.796 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.946 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.153 ±(99.9%) 0.014 ms/op
Iteration   1: 4.075 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.950 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  18.823 ms/op
                 listUser·p0.9999: 26.435 ms/op
                 listUser·p1.00:   27.820 ms/op

Iteration   2: 3.956 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  15.122 ms/op
                 listUser·p0.9999: 21.234 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   3: 4.170 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.105 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   7.723 ms/op
                 listUser·p0.999:  15.340 ms/op
                 listUser·p0.9999: 17.627 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236127
  mean =      4.065 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 227146 
    [ 5.000,  7.500) = 6873 
    [ 7.500, 10.000) = 1317 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.950 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     15.729 ms/op
     p(99.9900) =     24.995 ms/op
     p(99.9990) =     27.010 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.155 ± 3.174  ops/ms
ClientPb.existUser                       thrpt       3   9.668 ± 8.865  ops/ms
ClientPb.getUser                         thrpt       3   9.099 ± 3.245  ops/ms
ClientPb.listUser                        thrpt       3   7.996 ± 3.878  ops/ms
ClientPb.createUser                       avgt       3   3.452 ± 0.745   ms/op
ClientPb.existUser                        avgt       3   3.271 ± 0.301   ms/op
ClientPb.getUser                          avgt       3   3.484 ± 0.930   ms/op
ClientPb.listUser                         avgt       3   3.947 ± 1.984   ms/op
ClientPb.createUser                     sample  281268   3.412 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.217           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.112           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.464           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.542           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.886           ms/op
ClientPb.existUser                      sample  293549   3.267 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.255           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.224           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.826           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.368           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.247           ms/op
ClientPb.getUser                        sample  274398   3.497 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.395           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.407           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.333           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.528           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.246           ms/op
ClientPb.listUser                       sample  236127   4.065 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.950           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.299           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.729           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.995           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.820           ms/op
