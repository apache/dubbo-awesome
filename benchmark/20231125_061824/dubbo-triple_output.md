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
# Warmup Iteration   1: 4.977 ops/ms
# Warmup Iteration   2: 12.124 ops/ms
# Warmup Iteration   3: 12.389 ops/ms
Iteration   1: 12.590 ops/ms
Iteration   2: 12.731 ops/ms
Iteration   3: 12.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.675 ±(99.9%) 1.365 ops/ms [Average]
  (min, avg, max) = (12.590, 12.675, 12.731), stdev = 0.075
  CI (99.9%): [11.311, 14.040] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.127 ops/ms
# Warmup Iteration   2: 13.086 ops/ms
# Warmup Iteration   3: 12.987 ops/ms
Iteration   1: 13.077 ops/ms
Iteration   2: 13.095 ops/ms
Iteration   3: 13.160 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.111 ±(99.9%) 0.793 ops/ms [Average]
  (min, avg, max) = (13.077, 13.111, 13.160), stdev = 0.043
  CI (99.9%): [12.318, 13.904] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.972 ops/ms
# Warmup Iteration   2: 12.666 ops/ms
# Warmup Iteration   3: 13.010 ops/ms
Iteration   1: 13.020 ops/ms
Iteration   2: 12.871 ops/ms
Iteration   3: 12.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.938 ±(99.9%) 1.378 ops/ms [Average]
  (min, avg, max) = (12.871, 12.938, 13.020), stdev = 0.076
  CI (99.9%): [11.559, 14.316] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.376 ops/ms
# Warmup Iteration   2: 10.601 ops/ms
# Warmup Iteration   3: 10.600 ops/ms
Iteration   1: 10.709 ops/ms
Iteration   2: 10.791 ops/ms
Iteration   3: 10.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.740 ±(99.9%) 0.818 ops/ms [Average]
  (min, avg, max) = (10.709, 10.740, 10.791), stdev = 0.045
  CI (99.9%): [9.922, 11.557] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.875 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.491 ±(99.9%) 0.004 ms/op
Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
Iteration   3: 2.437 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.478 ±(99.9%) 0.664 ms/op [Average]
  (min, avg, max) = (2.437, 2.478, 2.507), stdev = 0.036
  CI (99.9%): [1.814, 3.143] (assumes normal distribution)


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
# Warmup Iteration   1: 3.593 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.417 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.414 ±(99.9%) 0.003 ms/op
Iteration   1: 2.426 ±(99.9%) 0.004 ms/op
Iteration   2: 2.415 ±(99.9%) 0.003 ms/op
Iteration   3: 2.421 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.420 ±(99.9%) 0.099 ms/op [Average]
  (min, avg, max) = (2.415, 2.420, 2.426), stdev = 0.005
  CI (99.9%): [2.321, 2.520] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.791 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.485 ±(99.9%) 0.004 ms/op
Iteration   1: 2.454 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.003 ms/op
Iteration   3: 2.512 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.486 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (2.454, 2.486, 2.512), stdev = 0.030
  CI (99.9%): [1.945, 3.027] (assumes normal distribution)


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
# Warmup Iteration   1: 4.730 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.005 ms/op
Iteration   1: 2.975 ±(99.9%) 0.006 ms/op
Iteration   2: 2.980 ±(99.9%) 0.005 ms/op
Iteration   3: 2.980 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.978 ±(99.9%) 0.050 ms/op [Average]
  (min, avg, max) = (2.975, 2.978, 2.980), stdev = 0.003
  CI (99.9%): [2.928, 3.028] (assumes normal distribution)


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
# Warmup Iteration   1: 4.224 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.006 ms/op
Iteration   1: 2.473 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.938 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   2.994 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.700 ms/op
                 createUser·p0.999:  8.806 ms/op
                 createUser·p0.9999: 20.319 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 2.503 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  10.235 ms/op
                 createUser·p0.9999: 12.596 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.547 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.634 ms/op
                 createUser·p0.999:  7.697 ms/op
                 createUser·p0.9999: 11.076 ms/op
                 createUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386034
  mean =      2.484 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 188216 
    [ 2.500,  5.000) = 196588 
    [ 5.000,  7.500) = 751 
    [ 7.500, 10.000) = 166 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.817 ms/op
     p(99.9000) =      9.617 ms/op
     p(99.9900) =     13.733 ms/op
     p(99.9990) =     20.517 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
Iteration   1: 2.432 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  8.513 ms/op
                 existUser·p0.9999: 18.345 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.826 ms/op
                 existUser·p0.999:  5.759 ms/op
                 existUser·p0.9999: 11.829 ms/op
                 existUser·p1.00:   12.206 ms/op

Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.854 ms/op
                 existUser·p0.999:  7.071 ms/op
                 existUser·p0.9999: 11.503 ms/op
                 existUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391320
  mean =      2.451 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 192794 
    [ 2.500,  3.750) = 194474 
    [ 3.750,  5.000) = 3149 
    [ 5.000,  6.250) = 425 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.768 ms/op
     p(99.9000) =      8.233 ms/op
     p(99.9900) =     13.760 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.560 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.511 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  11.628 ms/op
                 getUser·p0.9999: 14.541 ms/op
                 getUser·p1.00:   15.712 ms/op

Iteration   2: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  9.089 ms/op
                 getUser·p0.9999: 12.690 ms/op
                 getUser·p1.00:   14.008 ms/op

Iteration   3: 2.499 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  8.740 ms/op
                 getUser·p0.9999: 10.837 ms/op
                 getUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383946
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 189178 
    [ 2.500,  3.750) = 189119 
    [ 3.750,  5.000) = 4161 
    [ 5.000,  6.250) = 973 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      4.035 ms/op
     p(99.9000) =      8.815 ms/op
     p(99.9900) =     14.018 ms/op
     p(99.9990) =     14.748 ms/op
     p(99.9999) =     15.712 ms/op
    p(100.0000) =     15.712 ms/op


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
# Warmup Iteration   1: 4.865 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.009 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  8.512 ms/op
                 listUser·p0.9999: 11.174 ms/op
                 listUser·p1.00:   11.502 ms/op

Iteration   2: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.740 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 12.195 ms/op
                 listUser·p1.00:   12.960 ms/op

Iteration   3: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 12.009 ms/op
                 listUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320567
  mean =      2.992 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 95608 
    [ 2.500,  3.750) = 186239 
    [ 3.750,  5.000) = 31124 
    [ 5.000,  6.250) = 6112 
    [ 6.250,  7.500) = 714 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 221 
    [10.000, 11.250) = 156 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.581 ms/op
     p(99.9990) =     12.960 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.675 ± 1.365  ops/ms
ClientPb.existUser                       thrpt       3  13.111 ± 0.793  ops/ms
ClientPb.getUser                         thrpt       3  12.938 ± 1.378  ops/ms
ClientPb.listUser                        thrpt       3  10.740 ± 0.818  ops/ms
ClientPb.createUser                       avgt       3   2.478 ± 0.664   ms/op
ClientPb.existUser                        avgt       3   2.420 ± 0.099   ms/op
ClientPb.getUser                          avgt       3   2.486 ± 0.541   ms/op
ClientPb.listUser                         avgt       3   2.978 ± 0.050   ms/op
ClientPb.createUser                     sample  386034   2.484 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.547           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.011           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.133           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.617           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.733           ms/op
ClientPb.createUser:createUser·p1.00    sample          20.578           ms/op
ClientPb.existUser                      sample  391320   2.451 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.820           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.540           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.233           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.760           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.431           ms/op
ClientPb.getUser                        sample  383946   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.908           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.035           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.815           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.018           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.712           ms/op
ClientPb.listUser                       sample  320567   2.992 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.740           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.581           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.533           ms/op
