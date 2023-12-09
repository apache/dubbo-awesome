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
# Warmup Iteration   1: 5.076 ops/ms
# Warmup Iteration   2: 12.167 ops/ms
# Warmup Iteration   3: 12.434 ops/ms
Iteration   1: 12.732 ops/ms
Iteration   2: 12.801 ops/ms
Iteration   3: 12.841 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.791 ±(99.9%) 1.007 ops/ms [Average]
  (min, avg, max) = (12.732, 12.791, 12.841), stdev = 0.055
  CI (99.9%): [11.784, 13.799] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.433 ops/ms
# Warmup Iteration   2: 13.210 ops/ms
# Warmup Iteration   3: 13.302 ops/ms
Iteration   1: 13.287 ops/ms
Iteration   2: 13.263 ops/ms
Iteration   3: 13.190 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.247 ±(99.9%) 0.922 ops/ms [Average]
  (min, avg, max) = (13.190, 13.247, 13.287), stdev = 0.051
  CI (99.9%): [12.325, 14.168] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.070 ops/ms
# Warmup Iteration   2: 13.077 ops/ms
# Warmup Iteration   3: 13.278 ops/ms
Iteration   1: 13.374 ops/ms
Iteration   2: 13.293 ops/ms
Iteration   3: 13.319 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.329 ±(99.9%) 0.757 ops/ms [Average]
  (min, avg, max) = (13.293, 13.329, 13.374), stdev = 0.042
  CI (99.9%): [12.571, 14.086] (assumes normal distribution)


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
# Warmup Iteration   1: 6.882 ops/ms
# Warmup Iteration   2: 10.680 ops/ms
# Warmup Iteration   3: 10.844 ops/ms
Iteration   1: 10.889 ops/ms
Iteration   2: 10.848 ops/ms
Iteration   3: 10.806 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.848 ±(99.9%) 0.755 ops/ms [Average]
  (min, avg, max) = (10.806, 10.848, 10.889), stdev = 0.041
  CI (99.9%): [10.092, 11.603] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.004 ms/op
Iteration   2: 2.487 ±(99.9%) 0.004 ms/op
Iteration   3: 2.520 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.505 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (2.487, 2.505, 2.520), stdev = 0.017
  CI (99.9%): [2.200, 2.810] (assumes normal distribution)


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
# Warmup Iteration   1: 3.554 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.445 ±(99.9%) 0.004 ms/op
Iteration   1: 2.436 ±(99.9%) 0.003 ms/op
Iteration   2: 2.438 ±(99.9%) 0.004 ms/op
Iteration   3: 2.439 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.438 ±(99.9%) 0.032 ms/op [Average]
  (min, avg, max) = (2.436, 2.438, 2.439), stdev = 0.002
  CI (99.9%): [2.406, 2.469] (assumes normal distribution)


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
# Warmup Iteration   1: 3.924 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.486 ±(99.9%) 0.005 ms/op
Iteration   2: 2.497 ±(99.9%) 0.003 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (2.486, 2.490, 2.497), stdev = 0.006
  CI (99.9%): [2.375, 2.605] (assumes normal distribution)


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
# Warmup Iteration   1: 4.668 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.004 ms/op
Iteration   1: 2.975 ±(99.9%) 0.005 ms/op
Iteration   2: 2.944 ±(99.9%) 0.005 ms/op
Iteration   3: 2.941 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.953 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (2.941, 2.953, 2.975), stdev = 0.019
  CI (99.9%): [2.611, 3.295] (assumes normal distribution)


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
# Warmup Iteration   1: 4.284 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.625 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.015 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.768 ms/op
                 createUser·p0.999:  8.233 ms/op
                 createUser·p0.9999: 13.619 ms/op
                 createUser·p1.00:   14.549 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.809 ms/op
                 createUser·p0.999:  7.885 ms/op
                 createUser·p0.9999: 11.902 ms/op
                 createUser·p1.00:   12.763 ms/op

Iteration   3: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  8.610 ms/op
                 createUser·p0.9999: 10.322 ms/op
                 createUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385740
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 188252 
    [ 2.500,  3.750) = 193406 
    [ 3.750,  5.000) = 3284 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 106 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      8.589 ms/op
     p(99.9900) =     12.918 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.549 ms/op
    p(100.0000) =     14.549 ms/op


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
# Warmup Iteration   1: 3.824 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.447 ±(99.9%) 0.005 ms/op
Iteration   1: 2.424 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  5.849 ms/op
                 existUser·p0.9999: 13.894 ms/op
                 existUser·p1.00:   15.450 ms/op

Iteration   2: 2.442 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.147 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  8.046 ms/op
                 existUser·p0.9999: 13.057 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.978 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.990 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  8.785 ms/op
                 existUser·p0.9999: 11.779 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 393211
  mean =      2.439 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 194794 
    [ 2.500,  3.750) = 195683 
    [ 3.750,  5.000) = 2118 
    [ 5.000,  6.250) = 159 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.543 ms/op
     p(99.9000) =      7.873 ms/op
     p(99.9900) =     13.337 ms/op
     p(99.9990) =     14.415 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 3.905 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.006 ms/op
Iteration   1: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.674 ms/op
                 getUser·p0.999:  5.917 ms/op
                 getUser·p0.9999: 13.421 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   2: 2.455 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.858 ms/op
                 getUser·p0.999:  6.250 ms/op
                 getUser·p0.9999: 12.157 ms/op
                 getUser·p1.00:   13.058 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  5.980 ms/op
                 getUser·p0.9999: 10.623 ms/op
                 getUser·p1.00:   11.583 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388533
  mean =      2.469 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 195669 
    [ 2.500,  3.750) = 187684 
    [ 3.750,  5.000) = 4104 
    [ 5.000,  6.250) = 624 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      3.011 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =      5.980 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     14.090 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 4.528 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.008 ms/op
Iteration   1: 2.984 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.901 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.912 ms/op
                 listUser·p0.9999: 10.938 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   2: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.733 ms/op
                 listUser·p0.9999: 12.567 ms/op
                 listUser·p1.00:   13.386 ms/op

Iteration   3: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.858 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 10.441 ms/op
                 listUser·p1.00:   10.682 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320267
  mean =      2.994 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 96875 
    [ 2.500,  3.750) = 185802 
    [ 3.750,  5.000) = 30517 
    [ 5.000,  6.250) = 5523 
    [ 6.250,  7.500) = 617 
    [ 7.500,  8.750) = 238 
    [ 8.750, 10.000) = 377 
    [10.000, 11.250) = 159 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     11.484 ms/op
     p(99.9990) =     12.776 ms/op
     p(99.9999) =     13.386 ms/op
    p(100.0000) =     13.386 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.791 ± 1.007  ops/ms
ClientPb.existUser                       thrpt       3  13.247 ± 0.922  ops/ms
ClientPb.getUser                         thrpt       3  13.329 ± 0.757  ops/ms
ClientPb.listUser                        thrpt       3  10.848 ± 0.755  ops/ms
ClientPb.createUser                       avgt       3   2.505 ± 0.305   ms/op
ClientPb.existUser                        avgt       3   2.438 ± 0.032   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.115   ms/op
ClientPb.listUser                         avgt       3   2.953 ± 0.342   ms/op
ClientPb.createUser                     sample  385740   2.486 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.934           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.589           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.918           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.549           ms/op
ClientPb.existUser                      sample  393211   2.439 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.978           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.966           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.543           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.873           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.337           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.450           ms/op
ClientPb.getUser                        sample  388533   2.469 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.936           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.949           ms/op
ClientPb.getUser:getUser·p0.999         sample           5.980           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.189           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.139           ms/op
ClientPb.listUser                       sample  320267   2.994 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.858           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.601           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.484           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.386           ms/op
