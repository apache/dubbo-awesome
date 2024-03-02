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
# Warmup Iteration   1: 5.051 ops/ms
# Warmup Iteration   2: 12.100 ops/ms
# Warmup Iteration   3: 12.493 ops/ms
Iteration   1: 12.761 ops/ms
Iteration   2: 12.906 ops/ms
Iteration   3: 12.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.862 ±(99.9%) 1.601 ops/ms [Average]
  (min, avg, max) = (12.761, 12.862, 12.920), stdev = 0.088
  CI (99.9%): [11.261, 14.463] (assumes normal distribution)


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
# Warmup Iteration   1: 8.522 ops/ms
# Warmup Iteration   2: 13.491 ops/ms
# Warmup Iteration   3: 13.571 ops/ms
Iteration   1: 13.559 ops/ms
Iteration   2: 13.561 ops/ms
Iteration   3: 13.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.532 ±(99.9%) 0.901 ops/ms [Average]
  (min, avg, max) = (13.475, 13.532, 13.561), stdev = 0.049
  CI (99.9%): [12.631, 14.432] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.746 ops/ms
# Warmup Iteration   2: 12.818 ops/ms
# Warmup Iteration   3: 12.965 ops/ms
Iteration   1: 13.044 ops/ms
Iteration   2: 13.058 ops/ms
Iteration   3: 12.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.989 ±(99.9%) 1.941 ops/ms [Average]
  (min, avg, max) = (12.867, 12.989, 13.058), stdev = 0.106
  CI (99.9%): [11.049, 14.930] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.710 ops/ms
# Warmup Iteration   2: 10.584 ops/ms
# Warmup Iteration   3: 10.670 ops/ms
Iteration   1: 10.732 ops/ms
Iteration   2: 10.655 ops/ms
Iteration   3: 10.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.702 ±(99.9%) 0.747 ops/ms [Average]
  (min, avg, max) = (10.655, 10.702, 10.732), stdev = 0.041
  CI (99.9%): [9.955, 11.448] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.770 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.490 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.483 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (2.470, 2.483, 2.490), stdev = 0.011
  CI (99.9%): [2.275, 2.691] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.535 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.409 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.417 ±(99.9%) 0.004 ms/op
Iteration   1: 2.409 ±(99.9%) 0.004 ms/op
Iteration   2: 2.425 ±(99.9%) 0.004 ms/op
Iteration   3: 2.389 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.408 ±(99.9%) 0.326 ms/op [Average]
  (min, avg, max) = (2.389, 2.408, 2.425), stdev = 0.018
  CI (99.9%): [2.082, 2.733] (assumes normal distribution)


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
Iteration   1: 2.417 ±(99.9%) 0.004 ms/op
Iteration   2: 2.458 ±(99.9%) 0.003 ms/op
Iteration   3: 2.437 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.437 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (2.417, 2.437, 2.458), stdev = 0.021
  CI (99.9%): [2.062, 2.812] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.709 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
Iteration   2: 3.005 ±(99.9%) 0.003 ms/op
Iteration   3: 2.990 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.006 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (2.990, 3.006, 3.023), stdev = 0.017
  CI (99.9%): [2.703, 3.309] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 3.920 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.606 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.443 ±(99.9%) 0.005 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   2.523 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  6.606 ms/op
                 createUser·p0.9999: 17.003 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   2: 2.441 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   2.966 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   3.432 ms/op
                 createUser·p0.999:  6.884 ms/op
                 createUser·p0.9999: 15.612 ms/op
                 createUser·p1.00:   16.400 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   2.494 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   4.006 ms/op
                 createUser·p0.999:  8.100 ms/op
                 createUser·p0.9999: 11.227 ms/op
                 createUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 391082
  mean =      2.452 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 194542 
    [ 2.500,  3.750) = 192832 
    [ 3.750,  5.000) = 2688 
    [ 5.000,  6.250) = 515 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 127 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.088 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      7.714 ms/op
     p(99.9900) =     15.663 ms/op
     p(99.9990) =     17.272 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.420 ±(99.9%) 0.005 ms/op
Iteration   1: 2.407 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.019 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  5.624 ms/op
                 existUser·p0.9999: 13.823 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   2: 2.404 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.441 ms/op
                 existUser·p0.999:  7.887 ms/op
                 existUser·p0.9999: 13.125 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   3: 2.417 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   2.462 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  7.986 ms/op
                 existUser·p0.9999: 11.047 ms/op
                 existUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398016
  mean =      2.409 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 201886 
    [ 2.500,  3.750) = 193107 
    [ 3.750,  5.000) = 2270 
    [ 5.000,  6.250) = 276 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.572 ms/op
     p(99.9000) =      6.570 ms/op
     p(99.9900) =     13.504 ms/op
     p(99.9990) =     14.371 ms/op
     p(99.9999) =     14.860 ms/op
    p(100.0000) =     14.860 ms/op


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.577 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.609 ms/op
                 getUser·p0.999:  5.607 ms/op
                 getUser·p0.9999: 14.175 ms/op
                 getUser·p1.00:   14.828 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.994 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 13.631 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  7.361 ms/op
                 getUser·p0.9999: 11.796 ms/op
                 getUser·p1.00:   12.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385684
  mean =      2.487 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 192545 
    [ 2.500,  3.750) = 188778 
    [ 3.750,  5.000) = 3263 
    [ 5.000,  6.250) = 641 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 105 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      6.092 ms/op
     p(99.9900) =     13.910 ms/op
     p(99.9990) =     14.334 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 4.619 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.009 ms/op
Iteration   1: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.326 ms/op
                 listUser·p0.9999: 11.042 ms/op
                 listUser·p1.00:   11.862 ms/op

Iteration   2: 2.996 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 11.032 ms/op
                 listUser·p1.00:   11.993 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.629 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.093 ms/op
                 listUser·p0.9999: 10.888 ms/op
                 listUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319580
  mean =      3.001 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 93908 
    [ 2.500,  3.750) = 186459 
    [ 3.750,  5.000) = 31543 
    [ 5.000,  6.250) = 6267 
    [ 6.250,  7.500) = 573 
    [ 7.500,  8.750) = 245 
    [ 8.750, 10.000) = 257 
    [10.000, 11.250) = 162 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.231 ms/op
     p(99.9900) =     11.010 ms/op
     p(99.9990) =     11.731 ms/op
     p(99.9999) =     11.993 ms/op
    p(100.0000) =     11.993 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.862 ± 1.601  ops/ms
ClientPb.existUser                       thrpt       3  13.532 ± 0.901  ops/ms
ClientPb.getUser                         thrpt       3  12.989 ± 1.941  ops/ms
ClientPb.listUser                        thrpt       3  10.702 ± 0.747  ops/ms
ClientPb.createUser                       avgt       3   2.483 ± 0.208   ms/op
ClientPb.existUser                        avgt       3   2.408 ± 0.326   ms/op
ClientPb.getUser                          avgt       3   2.437 ± 0.375   ms/op
ClientPb.listUser                         avgt       3   3.006 ± 0.303   ms/op
ClientPb.createUser                     sample  391082   2.452 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.923           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.511           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.974           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.714           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.663           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.088           ms/op
ClientPb.existUser                      sample  398016   2.409 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.724           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.474           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.929           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.572           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.570           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.504           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.860           ms/op
ClientPb.getUser                        sample  385684   2.487 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.741           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.027           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.092           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.910           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.828           ms/op
ClientPb.listUser                       sample  319580   3.001 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.629           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.231           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.010           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.993           ms/op
