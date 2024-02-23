# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.192 ops/ms
# Warmup Iteration   2: 11.958 ops/ms
# Warmup Iteration   3: 12.402 ops/ms
Iteration   1: 12.468 ops/ms
Iteration   2: 12.512 ops/ms
Iteration   3: 12.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.536 ±(99.9%) 1.497 ops/ms [Average]
  (min, avg, max) = (12.468, 12.536, 12.627), stdev = 0.082
  CI (99.9%): [11.039, 14.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.904 ops/ms
# Warmup Iteration   2: 12.715 ops/ms
# Warmup Iteration   3: 12.919 ops/ms
Iteration   1: 12.978 ops/ms
Iteration   2: 12.718 ops/ms
Iteration   3: 12.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.879 ±(99.9%) 2.564 ops/ms [Average]
  (min, avg, max) = (12.718, 12.879, 12.978), stdev = 0.141
  CI (99.9%): [10.315, 15.443] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.377 ops/ms
# Warmup Iteration   2: 12.261 ops/ms
# Warmup Iteration   3: 12.654 ops/ms
Iteration   1: 12.558 ops/ms
Iteration   2: 12.501 ops/ms
Iteration   3: 12.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.583 ±(99.9%) 1.786 ops/ms [Average]
  (min, avg, max) = (12.501, 12.583, 12.692), stdev = 0.098
  CI (99.9%): [10.797, 14.370] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.424 ops/ms
# Warmup Iteration   2: 10.297 ops/ms
# Warmup Iteration   3: 10.262 ops/ms
Iteration   1: 10.189 ops/ms
Iteration   2: 10.362 ops/ms
Iteration   3: 10.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.255 ±(99.9%) 1.711 ops/ms [Average]
  (min, avg, max) = (10.189, 10.255, 10.362), stdev = 0.094
  CI (99.9%): [8.544, 11.966] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.091 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.646 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.004 ms/op
Iteration   1: 2.537 ±(99.9%) 0.004 ms/op
Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
Iteration   3: 2.532 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.529 ±(99.9%) 0.191 ms/op [Average]
  (min, avg, max) = (2.517, 2.529, 2.537), stdev = 0.010
  CI (99.9%): [2.338, 2.719] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.732 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
Iteration   3: 2.473 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.447 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (2.423, 2.447, 2.473), stdev = 0.025
  CI (99.9%): [1.990, 2.904] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.073 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.587 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.529 ±(99.9%) 0.004 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
Iteration   2: 2.518 ±(99.9%) 0.003 ms/op
Iteration   3: 2.518 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.011 ms/op [Average]
  (min, avg, max) = (2.517, 2.518, 2.518), stdev = 0.001
  CI (99.9%): [2.507, 2.529] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.911 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.005 ms/op
Iteration   1: 3.056 ±(99.9%) 0.006 ms/op
Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
Iteration   3: 3.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (3.037, 3.044, 3.056), stdev = 0.010
  CI (99.9%): [2.857, 3.231] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.271 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.714 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.586 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   3.994 ms/op
                 createUser·p0.999:  11.919 ms/op
                 createUser·p0.9999: 13.905 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.526 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  10.431 ms/op
                 createUser·p0.9999: 12.681 ms/op
                 createUser·p1.00:   13.058 ms/op

Iteration   3: 2.574 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.138 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   4.002 ms/op
                 createUser·p0.999:  8.795 ms/op
                 createUser·p0.9999: 14.254 ms/op
                 createUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373539
  mean =      2.568 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 177050 
    [ 2.500,  5.000) = 195639 
    [ 5.000,  7.500) = 450 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.265 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      8.871 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     15.002 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.724 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.486 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
Iteration   1: 2.461 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.367 ms/op
                 existUser·p0.999:  6.787 ms/op
                 existUser·p0.9999: 28.968 ms/op
                 existUser·p1.00:   29.688 ms/op

Iteration   2: 2.468 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.531 ms/op
                 existUser·p0.999:  6.425 ms/op
                 existUser·p0.9999: 13.583 ms/op
                 existUser·p1.00:   14.238 ms/op

Iteration   3: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.867 ms/op
                 existUser·p0.999:  8.554 ms/op
                 existUser·p0.9999: 12.005 ms/op
                 existUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390345
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 193900 
    [ 2.500,  5.000) = 195701 
    [ 5.000,  7.500) = 349 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.534 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      7.741 ms/op
     p(99.9900) =     14.072 ms/op
     p(99.9990) =     29.298 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.137 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   2.441 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  9.917 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.347 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  10.008 ms/op
                 getUser·p0.9999: 14.700 ms/op
                 getUser·p1.00:   15.696 ms/op

Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   3.789 ms/op
                 getUser·p0.999:  8.332 ms/op
                 getUser·p0.9999: 11.833 ms/op
                 getUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381507
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 175 
    [ 1.250,  2.500) = 192156 
    [ 2.500,  3.750) = 183861 
    [ 3.750,  5.000) = 4309 
    [ 5.000,  6.250) = 514 
    [ 6.250,  7.500) = 88 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.347 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.969 ms/op
     p(99.9000) =      8.368 ms/op
     p(99.9900) =     14.071 ms/op
     p(99.9990) =     15.112 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.868 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.008 ms/op
Iteration   1: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.634 ms/op
                 listUser·p0.9999: 11.305 ms/op
                 listUser·p1.00:   11.518 ms/op

Iteration   2: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.716 ms/op
                 listUser·p0.9999: 12.550 ms/op
                 listUser·p1.00:   13.730 ms/op

Iteration   3: 3.001 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.786 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 10.836 ms/op
                 listUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321098
  mean =      2.987 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 98467 
    [ 2.500,  3.750) = 184669 
    [ 3.750,  5.000) = 30459 
    [ 5.000,  6.250) = 6059 
    [ 6.250,  7.500) = 649 
    [ 7.500,  8.750) = 239 
    [ 8.750, 10.000) = 258 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =      9.224 ms/op
     p(99.9900) =     11.906 ms/op
     p(99.9990) =     13.647 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.536 ± 1.497  ops/ms
ClientPb.existUser                       thrpt       3  12.879 ± 2.564  ops/ms
ClientPb.getUser                         thrpt       3  12.583 ± 1.786  ops/ms
ClientPb.listUser                        thrpt       3  10.255 ± 1.711  ops/ms
ClientPb.createUser                       avgt       3   2.529 ± 0.191   ms/op
ClientPb.existUser                        avgt       3   2.447 ± 0.457   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.011   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.187   ms/op
ClientPb.createUser                     sample  373539   2.568 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.526           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.125           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.871           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.779           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.496           ms/op
ClientPb.existUser                      sample  390345   2.457 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.534           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.515           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.741           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.072           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.688           ms/op
ClientPb.getUser                        sample  381507   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.347           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.486           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.969           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.368           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.071           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.696           ms/op
ClientPb.listUser                       sample  321098   2.987 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.781           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.595           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.224           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.906           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.730           ms/op
