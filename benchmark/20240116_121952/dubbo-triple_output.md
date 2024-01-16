# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.536 ops/ms
# Warmup Iteration   2: 12.122 ops/ms
# Warmup Iteration   3: 12.259 ops/ms
Iteration   1: 12.539 ops/ms
Iteration   2: 12.458 ops/ms
Iteration   3: 12.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.514 ±(99.9%) 0.899 ops/ms [Average]
  (min, avg, max) = (12.458, 12.514, 12.546), stdev = 0.049
  CI (99.9%): [11.615, 13.413] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.974 ops/ms
# Warmup Iteration   2: 12.915 ops/ms
# Warmup Iteration   3: 12.901 ops/ms
Iteration   1: 12.884 ops/ms
Iteration   2: 12.860 ops/ms
Iteration   3: 12.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.880 ±(99.9%) 0.332 ops/ms [Average]
  (min, avg, max) = (12.860, 12.880, 12.896), stdev = 0.018
  CI (99.9%): [12.548, 13.212] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.436 ops/ms
# Warmup Iteration   2: 12.689 ops/ms
# Warmup Iteration   3: 12.853 ops/ms
Iteration   1: 12.880 ops/ms
Iteration   2: 12.763 ops/ms
Iteration   3: 13.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.897 ±(99.9%) 2.608 ops/ms [Average]
  (min, avg, max) = (12.763, 12.897, 13.048), stdev = 0.143
  CI (99.9%): [10.289, 15.505] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.724 ops/ms
# Warmup Iteration   2: 10.426 ops/ms
# Warmup Iteration   3: 10.540 ops/ms
Iteration   1: 10.662 ops/ms
Iteration   2: 10.619 ops/ms
Iteration   3: 10.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.644 ±(99.9%) 0.410 ops/ms [Average]
  (min, avg, max) = (10.619, 10.644, 10.662), stdev = 0.023
  CI (99.9%): [10.233, 11.054] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.998 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.537 ±(99.9%) 0.005 ms/op
Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
Iteration   3: 2.509 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.534 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (2.509, 2.534, 2.556), stdev = 0.024
  CI (99.9%): [2.103, 2.965] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.713 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.440 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.004 ms/op
Iteration   1: 2.448 ±(99.9%) 0.003 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (2.448, 2.458, 2.473), stdev = 0.013
  CI (99.9%): [2.213, 2.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.899 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.484 ±(99.9%) 0.003 ms/op
Iteration   3: 2.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.477 ±(99.9%) 0.114 ms/op [Average]
  (min, avg, max) = (2.473, 2.477, 2.484), stdev = 0.006
  CI (99.9%): [2.363, 2.591] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.645 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.007 ms/op
Iteration   1: 2.978 ±(99.9%) 0.006 ms/op
Iteration   2: 2.960 ±(99.9%) 0.005 ms/op
Iteration   3: 2.959 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.966 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (2.959, 2.966, 2.978), stdev = 0.011
  CI (99.9%): [2.773, 3.158] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.323 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.660 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
Iteration   1: 2.570 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  11.359 ms/op
                 createUser·p0.9999: 13.572 ms/op
                 createUser·p1.00:   14.664 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.996 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  9.257 ms/op
                 createUser·p0.9999: 12.229 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.668 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 10.554 ms/op
                 createUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379984
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 182037 
    [ 2.500,  3.750) = 194195 
    [ 3.750,  5.000) = 2655 
    [ 5.000,  6.250) = 514 
    [ 6.250,  7.500) = 139 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 125 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.736 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     14.375 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.878 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
Iteration   1: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  7.784 ms/op
                 existUser·p0.9999: 13.353 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   2: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.426 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  5.243 ms/op
                 existUser·p0.9999: 12.780 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   3: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   2.589 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  7.045 ms/op
                 existUser·p0.9999: 11.928 ms/op
                 existUser·p1.00:   13.025 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386090
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 187384 
    [ 2.500,  3.750) = 195646 
    [ 3.750,  5.000) = 2427 
    [ 5.000,  6.250) = 248 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      5.743 ms/op
     p(99.9900) =     13.091 ms/op
     p(99.9990) =     13.503 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.816 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.580 ms/op
                 getUser·p0.999:  9.733 ms/op
                 getUser·p0.9999: 13.752 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   2: 2.545 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.070 ms/op
                 getUser·p0.999:  9.380 ms/op
                 getUser·p0.9999: 14.252 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   3: 2.545 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  7.746 ms/op
                 getUser·p0.9999: 12.525 ms/op
                 getUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379528
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 185720 
    [ 2.500,  3.750) = 188807 
    [ 3.750,  5.000) = 3856 
    [ 5.000,  6.250) = 666 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 97 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      7.987 ms/op
     p(99.9900) =     13.681 ms/op
     p(99.9990) =     14.503 ms/op
     p(99.9999) =     14.565 ms/op
    p(100.0000) =     14.565 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.745 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.008 ms/op
Iteration   1: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  8.957 ms/op
                 listUser·p0.9999: 10.965 ms/op
                 listUser·p1.00:   11.403 ms/op

Iteration   2: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.770 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 13.263 ms/op
                 listUser·p1.00:   15.024 ms/op

Iteration   3: 2.968 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  8.983 ms/op
                 listUser·p0.9999: 11.443 ms/op
                 listUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323047
  mean =      2.969 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 99711 
    [ 2.500,  3.750) = 186925 
    [ 3.750,  5.000) = 29966 
    [ 5.000,  6.250) = 5168 
    [ 6.250,  7.500) = 491 
    [ 7.500,  8.750) = 236 
    [ 8.750, 10.000) = 268 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     12.128 ms/op
     p(99.9990) =     14.322 ms/op
     p(99.9999) =     15.024 ms/op
    p(100.0000) =     15.024 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.514 ± 0.899  ops/ms
ClientPb.existUser                       thrpt       3  12.880 ± 0.332  ops/ms
ClientPb.getUser                         thrpt       3  12.897 ± 2.608  ops/ms
ClientPb.listUser                        thrpt       3  10.644 ± 0.410  ops/ms
ClientPb.createUser                       avgt       3   2.534 ± 0.431   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.245   ms/op
ClientPb.getUser                          avgt       3   2.477 ± 0.114   ms/op
ClientPb.listUser                         avgt       3   2.966 ± 0.193   ms/op
ClientPb.createUser                     sample  379984   2.523 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.963           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.736           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.684           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.911           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.664           ms/op
ClientPb.existUser                      sample  386090   2.484 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.426           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.589           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.011           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.743           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.091           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.697           ms/op
ClientPb.getUser                        sample  379528   2.527 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.870           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.987           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.681           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.565           ms/op
ClientPb.listUser                       sample  323047   2.969 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.770           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.044           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.128           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.024           ms/op
