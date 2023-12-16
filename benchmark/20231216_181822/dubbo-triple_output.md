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
# Warmup Iteration   1: 5.254 ops/ms
# Warmup Iteration   2: 12.261 ops/ms
# Warmup Iteration   3: 12.500 ops/ms
Iteration   1: 12.786 ops/ms
Iteration   2: 12.887 ops/ms
Iteration   3: 12.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.819 ±(99.9%) 1.079 ops/ms [Average]
  (min, avg, max) = (12.784, 12.819, 12.887), stdev = 0.059
  CI (99.9%): [11.740, 13.898] (assumes normal distribution)


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
# Warmup Iteration   1: 8.266 ops/ms
# Warmup Iteration   2: 13.047 ops/ms
# Warmup Iteration   3: 13.331 ops/ms
Iteration   1: 13.311 ops/ms
Iteration   2: 13.297 ops/ms
Iteration   3: 13.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.295 ±(99.9%) 0.312 ops/ms [Average]
  (min, avg, max) = (13.277, 13.295, 13.311), stdev = 0.017
  CI (99.9%): [12.983, 13.607] (assumes normal distribution)


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
# Warmup Iteration   1: 7.926 ops/ms
# Warmup Iteration   2: 12.807 ops/ms
# Warmup Iteration   3: 13.074 ops/ms
Iteration   1: 13.138 ops/ms
Iteration   2: 13.094 ops/ms
Iteration   3: 13.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.124 ±(99.9%) 0.473 ops/ms [Average]
  (min, avg, max) = (13.094, 13.124, 13.141), stdev = 0.026
  CI (99.9%): [12.651, 13.598] (assumes normal distribution)


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
# Warmup Iteration   1: 6.860 ops/ms
# Warmup Iteration   2: 10.698 ops/ms
# Warmup Iteration   3: 10.801 ops/ms
Iteration   1: 10.797 ops/ms
Iteration   2: 10.792 ops/ms
Iteration   3: 10.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.772 ±(99.9%) 0.723 ops/ms [Average]
  (min, avg, max) = (10.726, 10.772, 10.797), stdev = 0.040
  CI (99.9%): [10.049, 11.495] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.639 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.004 ms/op
Iteration   1: 2.465 ±(99.9%) 0.004 ms/op
Iteration   2: 2.406 ±(99.9%) 0.004 ms/op
Iteration   3: 2.445 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.438 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (2.406, 2.438, 2.465), stdev = 0.030
  CI (99.9%): [1.888, 2.989] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.547 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.411 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.004 ms/op
Iteration   1: 2.412 ±(99.9%) 0.004 ms/op
Iteration   2: 2.413 ±(99.9%) 0.004 ms/op
Iteration   3: 2.408 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.411 ±(99.9%) 0.049 ms/op [Average]
  (min, avg, max) = (2.408, 2.411, 2.413), stdev = 0.003
  CI (99.9%): [2.362, 2.460] (assumes normal distribution)


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
# Warmup Iteration   1: 3.674 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.448 ±(99.9%) 0.004 ms/op
Iteration   1: 2.427 ±(99.9%) 0.004 ms/op
Iteration   2: 2.450 ±(99.9%) 0.003 ms/op
Iteration   3: 2.442 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.440 ±(99.9%) 0.210 ms/op [Average]
  (min, avg, max) = (2.427, 2.440, 2.450), stdev = 0.012
  CI (99.9%): [2.230, 2.650] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.613 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
Iteration   1: 2.987 ±(99.9%) 0.006 ms/op
Iteration   2: 2.953 ±(99.9%) 0.005 ms/op
Iteration   3: 2.952 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.964 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.952, 2.964, 2.987), stdev = 0.020
  CI (99.9%): [2.604, 3.324] (assumes normal distribution)


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
# Warmup Iteration   1: 4.071 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.658 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.006 ms/op
Iteration   1: 2.517 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   4.047 ms/op
                 createUser·p0.999:  12.057 ms/op
                 createUser·p0.9999: 17.039 ms/op
                 createUser·p1.00:   18.153 ms/op

Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  8.693 ms/op
                 createUser·p0.9999: 12.960 ms/op
                 createUser·p1.00:   13.337 ms/op

Iteration   3: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  9.172 ms/op
                 createUser·p0.9999: 10.797 ms/op
                 createUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 382613
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 185868 
    [ 2.500,  3.750) = 192097 
    [ 3.750,  5.000) = 3746 
    [ 5.000,  6.250) = 379 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      9.341 ms/op
     p(99.9900) =     15.925 ms/op
     p(99.9990) =     17.708 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.458 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
Iteration   1: 2.398 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.912 ms/op
                 existUser·p0.95:   3.011 ms/op
                 existUser·p0.99:   3.366 ms/op
                 existUser·p0.999:  5.118 ms/op
                 existUser·p0.9999: 16.799 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  7.822 ms/op
                 existUser·p0.9999: 14.713 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.871 ms/op
                 existUser·p0.999:  8.287 ms/op
                 existUser·p0.9999: 10.060 ms/op
                 existUser·p1.00:   10.945 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395055
  mean =      2.427 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 198864 
    [ 2.500,  3.750) = 192873 
    [ 3.750,  5.000) = 2579 
    [ 5.000,  6.250) = 251 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.486 ms/op
     p(90.0000) =      2.953 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      8.167 ms/op
     p(99.9900) =     14.795 ms/op
     p(99.9990) =     17.334 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 3.869 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.006 ms/op
Iteration   1: 2.468 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.703 ms/op
                 getUser·p0.999:  7.397 ms/op
                 getUser·p0.9999: 13.502 ms/op
                 getUser·p1.00:   14.795 ms/op

Iteration   2: 2.467 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.998 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.514 ms/op
                 getUser·p0.999:  6.635 ms/op
                 getUser·p0.9999: 12.667 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   3: 2.501 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  9.653 ms/op
                 getUser·p0.9999: 17.086 ms/op
                 getUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387005
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 193282 
    [ 2.500,  5.000) = 192759 
    [ 5.000,  7.500) = 559 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     14.030 ms/op
     p(99.9990) =     23.855 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 4.688 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.008 ms/op
Iteration   1: 2.972 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.889 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  8.897 ms/op
                 listUser·p0.9999: 10.113 ms/op
                 listUser·p1.00:   10.306 ms/op

Iteration   2: 2.966 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  8.769 ms/op
                 listUser·p0.9999: 11.784 ms/op
                 listUser·p1.00:   12.419 ms/op

Iteration   3: 2.970 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.880 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.044 ms/op
                 listUser·p0.9999: 10.781 ms/op
                 listUser·p1.00:   11.158 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323004
  mean =      2.969 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 100201 
    [ 2.500,  3.750) = 186376 
    [ 3.750,  5.000) = 29430 
    [ 5.000,  6.250) = 5489 
    [ 6.250,  7.500) = 708 
    [ 7.500,  8.750) = 297 
    [ 8.750, 10.000) = 248 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.529 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     11.092 ms/op
     p(99.9990) =     12.256 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.819 ± 1.079  ops/ms
ClientPb.existUser                       thrpt       3  13.295 ± 0.312  ops/ms
ClientPb.getUser                         thrpt       3  13.124 ± 0.473  ops/ms
ClientPb.listUser                        thrpt       3  10.772 ± 0.723  ops/ms
ClientPb.createUser                       avgt       3   2.438 ± 0.550   ms/op
ClientPb.existUser                        avgt       3   2.411 ± 0.049   ms/op
ClientPb.getUser                          avgt       3   2.440 ± 0.210   ms/op
ClientPb.listUser                         avgt       3   2.964 ± 0.360   ms/op
ClientPb.createUser                     sample  382613   2.507 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.695           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.854           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.341           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.925           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.153           ms/op
ClientPb.existUser                      sample  395055   2.427 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.752           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.486           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.953           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.064           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.167           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.795           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.531           ms/op
ClientPb.getUser                        sample  387005   2.478 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.655           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.503           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.002           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.650           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.030           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.953           ms/op
ClientPb.listUser                       sample  323004   2.969 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.802           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.529           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.913           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.092           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.419           ms/op
