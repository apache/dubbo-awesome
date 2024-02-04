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
# Warmup Iteration   1: 4.013 ops/ms
# Warmup Iteration   2: 11.775 ops/ms
# Warmup Iteration   3: 12.348 ops/ms
Iteration   1: 12.455 ops/ms
Iteration   2: 12.624 ops/ms
Iteration   3: 12.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.622 ±(99.9%) 3.023 ops/ms [Average]
  (min, avg, max) = (12.455, 12.622, 12.786), stdev = 0.166
  CI (99.9%): [9.599, 15.645] (assumes normal distribution)


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
# Warmup Iteration   1: 7.771 ops/ms
# Warmup Iteration   2: 12.834 ops/ms
# Warmup Iteration   3: 12.924 ops/ms
Iteration   1: 13.064 ops/ms
Iteration   2: 13.061 ops/ms
Iteration   3: 12.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.994 ±(99.9%) 2.153 ops/ms [Average]
  (min, avg, max) = (12.858, 12.994, 13.064), stdev = 0.118
  CI (99.9%): [10.842, 15.147] (assumes normal distribution)


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
# Warmup Iteration   1: 7.468 ops/ms
# Warmup Iteration   2: 12.324 ops/ms
# Warmup Iteration   3: 12.689 ops/ms
Iteration   1: 12.791 ops/ms
Iteration   2: 12.543 ops/ms
Iteration   3: 12.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.615 ±(99.9%) 2.792 ops/ms [Average]
  (min, avg, max) = (12.511, 12.615, 12.791), stdev = 0.153
  CI (99.9%): [9.823, 15.407] (assumes normal distribution)


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
# Warmup Iteration   1: 6.613 ops/ms
# Warmup Iteration   2: 10.676 ops/ms
# Warmup Iteration   3: 10.660 ops/ms
Iteration   1: 10.667 ops/ms
Iteration   2: 10.663 ops/ms
Iteration   3: 10.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.674 ±(99.9%) 0.306 ops/ms [Average]
  (min, avg, max) = (10.663, 10.674, 10.694), stdev = 0.017
  CI (99.9%): [10.368, 10.981] (assumes normal distribution)


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
# Warmup Iteration   1: 4.211 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.594 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.004 ms/op
Iteration   1: 2.549 ±(99.9%) 0.004 ms/op
Iteration   2: 2.531 ±(99.9%) 0.003 ms/op
Iteration   3: 2.546 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.542 ±(99.9%) 0.181 ms/op [Average]
  (min, avg, max) = (2.531, 2.542, 2.549), stdev = 0.010
  CI (99.9%): [2.361, 2.722] (assumes normal distribution)


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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.452 ±(99.9%) 0.004 ms/op
Iteration   1: 2.430 ±(99.9%) 0.004 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.431 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.434 ±(99.9%) 0.109 ms/op [Average]
  (min, avg, max) = (2.430, 2.434, 2.441), stdev = 0.006
  CI (99.9%): [2.324, 2.543] (assumes normal distribution)


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.003 ms/op
Iteration   2: 2.508 ±(99.9%) 0.004 ms/op
Iteration   3: 2.533 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.514 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (2.502, 2.514, 2.533), stdev = 0.016
  CI (99.9%): [2.218, 2.810] (assumes normal distribution)


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
# Warmup Iteration   1: 4.635 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.005 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
Iteration   3: 3.036 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.041 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (3.029, 3.041, 3.059), stdev = 0.016
  CI (99.9%): [2.755, 3.327] (assumes normal distribution)


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
# Warmup Iteration   1: 4.242 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.680 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
Iteration   1: 2.513 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.126 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  11.893 ms/op
                 createUser·p0.9999: 14.203 ms/op
                 createUser·p1.00:   15.450 ms/op

Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.961 ms/op
                 createUser·p0.999:  9.699 ms/op
                 createUser·p0.9999: 11.862 ms/op
                 createUser·p1.00:   12.698 ms/op

Iteration   3: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.546 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  8.405 ms/op
                 createUser·p0.9999: 11.462 ms/op
                 createUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380284
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 184059 
    [ 2.500,  3.750) = 192266 
    [ 3.750,  5.000) = 2997 
    [ 5.000,  6.250) = 369 
    [ 6.250,  7.500) = 108 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.170 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     13.418 ms/op
     p(99.9990) =     14.819 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.443 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.440 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  7.520 ms/op
                 existUser·p0.9999: 13.547 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  7.957 ms/op
                 existUser·p0.9999: 12.712 ms/op
                 existUser·p1.00:   13.369 ms/op

Iteration   3: 2.425 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  5.644 ms/op
                 existUser·p0.9999: 11.659 ms/op
                 existUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393746
  mean =      2.436 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 198934 
    [ 2.500,  3.750) = 191498 
    [ 3.750,  5.000) = 2578 
    [ 5.000,  6.250) = 241 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      7.442 ms/op
     p(99.9900) =     13.042 ms/op
     p(99.9990) =     14.011 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.486 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  10.053 ms/op
                 getUser·p0.9999: 14.172 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   2: 2.523 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  9.594 ms/op
                 getUser·p0.9999: 11.747 ms/op
                 getUser·p1.00:   12.190 ms/op

Iteration   3: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.662 ms/op
                 getUser·p0.999:  6.725 ms/op
                 getUser·p0.9999: 12.374 ms/op
                 getUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384135
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 190408 
    [ 2.500,  3.750) = 188360 
    [ 3.750,  5.000) = 3909 
    [ 5.000,  6.250) = 925 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 115 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.985 ms/op
     p(99.9000) =      8.296 ms/op
     p(99.9900) =     13.477 ms/op
     p(99.9990) =     14.584 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 4.572 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.009 ms/op
Iteration   1: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.702 ms/op
                 listUser·p0.999:  9.273 ms/op
                 listUser·p0.9999: 15.093 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   2: 2.997 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.935 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.454 ms/op
                 listUser·p0.9999: 10.491 ms/op
                 listUser·p1.00:   11.370 ms/op

Iteration   3: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.942 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.667 ms/op
                 listUser·p0.9999: 16.650 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318167
  mean =      3.014 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 93550 
    [ 2.500,  5.000) = 217121 
    [ 5.000,  7.500) = 6788 
    [ 7.500, 10.000) = 523 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     16.062 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.622 ± 3.023  ops/ms
ClientPb.existUser                       thrpt       3  12.994 ± 2.153  ops/ms
ClientPb.getUser                         thrpt       3  12.615 ± 2.792  ops/ms
ClientPb.listUser                        thrpt       3  10.674 ± 0.306  ops/ms
ClientPb.createUser                       avgt       3   2.542 ± 0.181   ms/op
ClientPb.existUser                        avgt       3   2.434 ± 0.109   ms/op
ClientPb.getUser                          avgt       3   2.514 ± 0.296   ms/op
ClientPb.listUser                         avgt       3   3.041 ± 0.286   ms/op
ClientPb.createUser                     sample  380284   2.522 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.546           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.170           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.913           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.418           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.450           ms/op
ClientPb.existUser                      sample  393746   2.436 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.737           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.442           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.042           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  384135   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.681           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.519           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.296           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.477           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.991           ms/op
ClientPb.listUser                       sample  318167   3.014 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.935           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.062           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.185           ms/op
