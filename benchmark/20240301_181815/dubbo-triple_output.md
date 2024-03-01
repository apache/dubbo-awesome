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
# Warmup Iteration   1: 4.950 ops/ms
# Warmup Iteration   2: 11.934 ops/ms
# Warmup Iteration   3: 12.487 ops/ms
Iteration   1: 12.852 ops/ms
Iteration   2: 12.706 ops/ms
Iteration   3: 12.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.762 ±(99.9%) 1.443 ops/ms [Average]
  (min, avg, max) = (12.706, 12.762, 12.852), stdev = 0.079
  CI (99.9%): [11.318, 14.205] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.480 ops/ms
# Warmup Iteration   2: 13.380 ops/ms
# Warmup Iteration   3: 13.319 ops/ms
Iteration   1: 13.503 ops/ms
Iteration   2: 13.280 ops/ms
Iteration   3: 13.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.416 ±(99.9%) 2.171 ops/ms [Average]
  (min, avg, max) = (13.280, 13.416, 13.503), stdev = 0.119
  CI (99.9%): [11.245, 15.587] (assumes normal distribution)


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
# Warmup Iteration   1: 7.748 ops/ms
# Warmup Iteration   2: 12.709 ops/ms
# Warmup Iteration   3: 12.730 ops/ms
Iteration   1: 12.852 ops/ms
Iteration   2: 12.853 ops/ms
Iteration   3: 12.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.890 ±(99.9%) 1.186 ops/ms [Average]
  (min, avg, max) = (12.852, 12.890, 12.965), stdev = 0.065
  CI (99.9%): [11.704, 14.076] (assumes normal distribution)


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
# Warmup Iteration   1: 6.628 ops/ms
# Warmup Iteration   2: 10.520 ops/ms
# Warmup Iteration   3: 10.796 ops/ms
Iteration   1: 10.750 ops/ms
Iteration   2: 10.724 ops/ms
Iteration   3: 10.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.707 ±(99.9%) 0.976 ops/ms [Average]
  (min, avg, max) = (10.647, 10.707, 10.750), stdev = 0.054
  CI (99.9%): [9.731, 11.684] (assumes normal distribution)


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.003 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.506 ±(99.9%) 0.004 ms/op
Iteration   3: 2.493 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.500 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (2.493, 2.500, 2.506), stdev = 0.007
  CI (99.9%): [2.376, 2.625] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.539 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.439 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.453 ±(99.9%) 0.004 ms/op
Iteration   1: 2.430 ±(99.9%) 0.004 ms/op
Iteration   2: 2.408 ±(99.9%) 0.004 ms/op
Iteration   3: 2.410 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.416 ±(99.9%) 0.226 ms/op [Average]
  (min, avg, max) = (2.408, 2.416, 2.430), stdev = 0.012
  CI (99.9%): [2.190, 2.642] (assumes normal distribution)


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
# Warmup Iteration   1: 3.739 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.455 ±(99.9%) 0.003 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.480 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.469 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (2.455, 2.469, 2.480), stdev = 0.013
  CI (99.9%): [2.231, 2.707] (assumes normal distribution)


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
# Warmup Iteration   1: 4.571 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
Iteration   1: 2.929 ±(99.9%) 0.006 ms/op
Iteration   2: 2.953 ±(99.9%) 0.005 ms/op
Iteration   3: 2.969 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.951 ±(99.9%) 0.366 ms/op [Average]
  (min, avg, max) = (2.929, 2.951, 2.969), stdev = 0.020
  CI (99.9%): [2.585, 3.316] (assumes normal distribution)


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
# Warmup Iteration   1: 4.345 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.688 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.550 ±(99.9%) 0.006 ms/op
Iteration   1: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  11.543 ms/op
                 createUser·p0.9999: 13.938 ms/op
                 createUser·p1.00:   14.434 ms/op

Iteration   2: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 14.670 ms/op
                 createUser·p1.00:   15.122 ms/op

Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  8.701 ms/op
                 createUser·p0.9999: 10.633 ms/op
                 createUser·p1.00:   10.813 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378526
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 182791 
    [ 2.500,  3.750) = 191761 
    [ 3.750,  5.000) = 2903 
    [ 5.000,  6.250) = 450 
    [ 6.250,  7.500) = 141 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 123 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.790 ms/op
     p(99.9900) =     13.959 ms/op
     p(99.9990) =     15.044 ms/op
     p(99.9999) =     15.122 ms/op
    p(100.0000) =     15.122 ms/op


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
# Warmup Iteration   1: 3.628 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.407 ±(99.9%) 0.005 ms/op
Iteration   1: 2.405 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.023 ms/op
                 existUser·p0.99:   3.539 ms/op
                 existUser·p0.999:  7.313 ms/op
                 existUser·p0.9999: 13.500 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   2: 2.377 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   2.408 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   3.006 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  7.434 ms/op
                 existUser·p0.9999: 14.141 ms/op
                 existUser·p1.00:   15.155 ms/op

Iteration   3: 2.365 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.871 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   3.604 ms/op
                 existUser·p0.999:  5.848 ms/op
                 existUser·p0.9999: 10.911 ms/op
                 existUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 402586
  mean =      2.382 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 87 
    [ 1.250,  2.500) = 210564 
    [ 2.500,  3.750) = 188888 
    [ 3.750,  5.000) = 2320 
    [ 5.000,  6.250) = 258 
    [ 6.250,  7.500) = 107 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      2.896 ms/op
     p(95.0000) =      3.011 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      6.937 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     14.418 ms/op
     p(99.9999) =     15.155 ms/op
    p(100.0000) =     15.155 ms/op


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
# Warmup Iteration   1: 4.140 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.511 ±(99.9%) 0.006 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.641 ms/op
                 getUser·p0.999:  9.333 ms/op
                 getUser·p0.9999: 13.615 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.957 ms/op
                 getUser·p0.999:  9.779 ms/op
                 getUser·p0.9999: 12.894 ms/op
                 getUser·p1.00:   13.189 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.919 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  8.802 ms/op
                 getUser·p0.9999: 10.764 ms/op
                 getUser·p1.00:   11.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383551
  mean =      2.501 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 189152 
    [ 2.500,  3.750) = 189506 
    [ 3.750,  5.000) = 3826 
    [ 5.000,  6.250) = 533 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      8.850 ms/op
     p(99.9900) =     13.227 ms/op
     p(99.9990) =     14.393 ms/op
     p(99.9999) =     14.483 ms/op
    p(100.0000) =     14.483 ms/op


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
# Warmup Iteration   1: 4.672 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.009 ms/op
Iteration   1: 3.020 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.585 ms/op
                 listUser·p0.9999: 11.250 ms/op
                 listUser·p1.00:   11.911 ms/op

Iteration   2: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.295 ms/op
                 listUser·p0.9999: 10.624 ms/op
                 listUser·p1.00:   13.631 ms/op

Iteration   3: 3.012 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.846 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 11.158 ms/op
                 listUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317646
  mean =      3.019 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 91758 
    [ 2.500,  3.750) = 185514 
    [ 3.750,  5.000) = 32539 
    [ 5.000,  6.250) = 6283 
    [ 6.250,  7.500) = 726 
    [ 7.500,  8.750) = 195 
    [ 8.750, 10.000) = 315 
    [10.000, 11.250) = 169 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.846 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.640 ms/op
     p(99.9900) =     11.059 ms/op
     p(99.9990) =     11.777 ms/op
     p(99.9999) =     13.631 ms/op
    p(100.0000) =     13.631 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.762 ± 1.443  ops/ms
ClientPb.existUser                       thrpt       3  13.416 ± 2.171  ops/ms
ClientPb.getUser                         thrpt       3  12.890 ± 1.186  ops/ms
ClientPb.listUser                        thrpt       3  10.707 ± 0.976  ops/ms
ClientPb.createUser                       avgt       3   2.500 ± 0.125   ms/op
ClientPb.existUser                        avgt       3   2.416 ± 0.226   ms/op
ClientPb.getUser                          avgt       3   2.469 ± 0.238   ms/op
ClientPb.listUser                         avgt       3   2.951 ± 0.366   ms/op
ClientPb.createUser                     sample  378526   2.533 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.932           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.790           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.959           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.122           ms/op
ClientPb.existUser                      sample  402586   2.382 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.855           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.433           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.896           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.937           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.500           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.155           ms/op
ClientPb.getUser                        sample  383551   2.501 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.701           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.850           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.227           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.483           ms/op
ClientPb.listUser                       sample  317646   3.019 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.846           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.640           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.059           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.631           ms/op
