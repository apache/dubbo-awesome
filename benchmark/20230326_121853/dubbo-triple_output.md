# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.014 ops/ms
# Warmup Iteration   2: 5.350 ops/ms
# Warmup Iteration   3: 8.371 ops/ms
Iteration   1: 9.197 ops/ms
Iteration   2: 9.531 ops/ms
Iteration   3: 9.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.310 ±(99.9%) 3.498 ops/ms [Average]
  (min, avg, max) = (9.197, 9.310, 9.531), stdev = 0.192
  CI (99.9%): [5.812, 12.808] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.202 ops/ms
# Warmup Iteration   2: 8.951 ops/ms
# Warmup Iteration   3: 9.496 ops/ms
Iteration   1: 10.127 ops/ms
Iteration   2: 9.986 ops/ms
Iteration   3: 9.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.944 ±(99.9%) 3.795 ops/ms [Average]
  (min, avg, max) = (9.718, 9.944, 10.127), stdev = 0.208
  CI (99.9%): [6.149, 13.739] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.135 ops/ms
# Warmup Iteration   2: 8.428 ops/ms
# Warmup Iteration   3: 9.176 ops/ms
Iteration   1: 9.528 ops/ms
Iteration   2: 9.239 ops/ms
Iteration   3: 9.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.518 ±(99.9%) 5.000 ops/ms [Average]
  (min, avg, max) = (9.239, 9.518, 9.787), stdev = 0.274
  CI (99.9%): [4.518, 14.518] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.994 ops/ms
# Warmup Iteration   2: 7.037 ops/ms
# Warmup Iteration   3: 7.609 ops/ms
Iteration   1: 8.095 ops/ms
Iteration   2: 8.134 ops/ms
Iteration   3: 7.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.066 ±(99.9%) 1.594 ops/ms [Average]
  (min, avg, max) = (7.967, 8.066, 8.134), stdev = 0.087
  CI (99.9%): [6.472, 9.659] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.762 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.581 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.012 ms/op
Iteration   1: 3.353 ±(99.9%) 0.008 ms/op
Iteration   2: 3.302 ±(99.9%) 0.010 ms/op
Iteration   3: 3.343 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.333 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (3.302, 3.333, 3.353), stdev = 0.027
  CI (99.9%): [2.835, 3.831] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.373 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.463 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.230 ±(99.9%) 0.006 ms/op
Iteration   1: 3.144 ±(99.9%) 0.011 ms/op
Iteration   2: 3.240 ±(99.9%) 0.005 ms/op
Iteration   3: 3.292 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.225 ±(99.9%) 1.375 ms/op [Average]
  (min, avg, max) = (3.144, 3.225, 3.292), stdev = 0.075
  CI (99.9%): [1.851, 4.600] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.486 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.856 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.007 ms/op
Iteration   1: 3.296 ±(99.9%) 0.004 ms/op
Iteration   2: 3.315 ±(99.9%) 0.008 ms/op
Iteration   3: 3.355 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.322 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (3.296, 3.322, 3.355), stdev = 0.030
  CI (99.9%): [2.774, 3.870] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.531 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.452 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.009 ms/op
Iteration   1: 3.933 ±(99.9%) 0.011 ms/op
Iteration   2: 3.899 ±(99.9%) 0.010 ms/op
Iteration   3: 3.871 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.901 ±(99.9%) 0.570 ms/op [Average]
  (min, avg, max) = (3.871, 3.901, 3.933), stdev = 0.031
  CI (99.9%): [3.331, 4.471] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.545 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.010 ms/op
Iteration   1: 3.406 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  19.210 ms/op
                 createUser·p0.9999: 24.066 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   2: 3.356 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.208 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  20.695 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   3: 3.298 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.538 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.038 ms/op
                 createUser·p0.999:  18.386 ms/op
                 createUser·p0.9999: 28.443 ms/op
                 createUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286052
  mean =      3.353 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6447 
    [ 2.500,  5.000) = 274543 
    [ 5.000,  7.500) = 4110 
    [ 7.500, 10.000) = 504 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     18.759 ms/op
     p(99.9900) =     27.171 ms/op
     p(99.9990) =     28.808 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.036 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.009 ms/op
Iteration   1: 3.351 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   6.496 ms/op
                 existUser·p0.999:  18.323 ms/op
                 existUser·p0.9999: 22.803 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   2: 3.295 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.724 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  19.694 ms/op
                 existUser·p0.9999: 25.765 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 3.193 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.784 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  9.564 ms/op
                 existUser·p0.9999: 26.803 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293001
  mean =      3.278 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19308 
    [ 2.500,  5.000) = 267569 
    [ 5.000,  7.500) = 5439 
    [ 7.500, 10.000) = 351 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 55 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     10.633 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     27.237 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.410 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.009 ms/op
Iteration   1: 3.526 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.897 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   7.651 ms/op
                 getUser·p0.999:  14.582 ms/op
                 getUser·p0.9999: 23.230 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.456 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.998 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.243 ms/op
                 getUser·p0.999:  21.034 ms/op
                 getUser·p0.9999: 24.871 ms/op
                 getUser·p1.00:   25.919 ms/op

Iteration   3: 3.496 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  17.581 ms/op
                 getUser·p0.9999: 44.162 ms/op
                 getUser·p1.00:   45.416 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274936
  mean =      3.493 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 266160 
    [ 5.000, 10.000) = 8355 
    [10.000, 15.000) = 143 
    [15.000, 20.000) = 50 
    [20.000, 25.000) = 157 
    [25.000, 30.000) = 7 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     17.533 ms/op
     p(99.9900) =     42.009 ms/op
     p(99.9990) =     45.253 ms/op
     p(99.9999) =     45.416 ms/op
    p(100.0000) =     45.416 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.950 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.505 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.013 ms/op
Iteration   1: 4.132 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   7.840 ms/op
                 listUser·p0.999:  20.937 ms/op
                 listUser·p0.9999: 25.756 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   2: 3.943 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.878 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  15.956 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   3: 4.009 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.478 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 21.202 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238455
  mean =      4.027 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 229471 
    [ 5.000,  7.500) = 6631 
    [ 7.500, 10.000) = 1556 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.366 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     27.608 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.310 ± 3.498  ops/ms
ClientPb.existUser                       thrpt       3   9.944 ± 3.795  ops/ms
ClientPb.getUser                         thrpt       3   9.518 ± 5.000  ops/ms
ClientPb.listUser                        thrpt       3   8.066 ± 1.594  ops/ms
ClientPb.createUser                       avgt       3   3.333 ± 0.498   ms/op
ClientPb.existUser                        avgt       3   3.225 ± 1.375   ms/op
ClientPb.getUser                          avgt       3   3.322 ± 0.548   ms/op
ClientPb.listUser                         avgt       3   3.901 ± 0.570   ms/op
ClientPb.createUser                     sample  286052   3.353 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.208           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.759           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.759           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.171           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.098           ms/op
ClientPb.existUser                      sample  293001   3.278 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.223           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.219           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.969           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.633           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.723           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  274936   3.493 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.897           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.010           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.530           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.533           ms/op
ClientPb.getUser:getUser·p0.9999        sample          42.009           ms/op
ClientPb.getUser:getUser·p1.00          sample          45.416           ms/op
ClientPb.listUser                       sample  238455   4.027 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.366           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.843           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.921           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.229           ms/op
