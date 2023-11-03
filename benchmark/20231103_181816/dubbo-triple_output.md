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
# Warmup Iteration   1: 4.420 ops/ms
# Warmup Iteration   2: 11.799 ops/ms
# Warmup Iteration   3: 12.228 ops/ms
Iteration   1: 12.510 ops/ms
Iteration   2: 12.349 ops/ms
Iteration   3: 12.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.424 ±(99.9%) 1.479 ops/ms [Average]
  (min, avg, max) = (12.349, 12.424, 12.510), stdev = 0.081
  CI (99.9%): [10.946, 13.903] (assumes normal distribution)


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
# Warmup Iteration   1: 8.145 ops/ms
# Warmup Iteration   2: 12.471 ops/ms
# Warmup Iteration   3: 12.693 ops/ms
Iteration   1: 12.648 ops/ms
Iteration   2: 12.812 ops/ms
Iteration   3: 12.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.726 ±(99.9%) 1.501 ops/ms [Average]
  (min, avg, max) = (12.648, 12.726, 12.812), stdev = 0.082
  CI (99.9%): [11.225, 14.226] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.983 ops/ms
# Warmup Iteration   2: 12.149 ops/ms
# Warmup Iteration   3: 12.280 ops/ms
Iteration   1: 12.243 ops/ms
Iteration   2: 12.443 ops/ms
Iteration   3: 12.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.353 ±(99.9%) 1.852 ops/ms [Average]
  (min, avg, max) = (12.243, 12.353, 12.443), stdev = 0.102
  CI (99.9%): [10.502, 14.205] (assumes normal distribution)


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
# Warmup Iteration   1: 6.410 ops/ms
# Warmup Iteration   2: 10.247 ops/ms
# Warmup Iteration   3: 10.370 ops/ms
Iteration   1: 10.546 ops/ms
Iteration   2: 10.471 ops/ms
Iteration   3: 10.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.560 ±(99.9%) 1.752 ops/ms [Average]
  (min, avg, max) = (10.471, 10.560, 10.662), stdev = 0.096
  CI (99.9%): [8.808, 12.311] (assumes normal distribution)


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.624 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.616 ±(99.9%) 0.004 ms/op
Iteration   1: 2.615 ±(99.9%) 0.004 ms/op
Iteration   2: 2.630 ±(99.9%) 0.004 ms/op
Iteration   3: 2.573 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.606 ±(99.9%) 0.540 ms/op [Average]
  (min, avg, max) = (2.573, 2.606, 2.630), stdev = 0.030
  CI (99.9%): [2.066, 3.146] (assumes normal distribution)


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.508 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.005 ms/op
Iteration   1: 2.518 ±(99.9%) 0.004 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.520 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (2.518, 2.520, 2.523), stdev = 0.003
  CI (99.9%): [2.472, 2.567] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.653 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.571 ±(99.9%) 0.004 ms/op
Iteration   1: 2.567 ±(99.9%) 0.004 ms/op
Iteration   2: 2.583 ±(99.9%) 0.005 ms/op
Iteration   3: 2.565 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.571 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (2.565, 2.571, 2.583), stdev = 0.010
  CI (99.9%): [2.392, 2.751] (assumes normal distribution)


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
# Warmup Iteration   1: 4.818 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
Iteration   1: 3.063 ±(99.9%) 0.005 ms/op
Iteration   2: 3.043 ±(99.9%) 0.005 ms/op
Iteration   3: 3.066 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.057 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (3.043, 3.057, 3.066), stdev = 0.012
  CI (99.9%): [2.833, 3.281] (assumes normal distribution)


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
# Warmup Iteration   1: 4.361 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.720 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.613 ±(99.9%) 0.006 ms/op
Iteration   1: 2.579 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   2.658 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   3.891 ms/op
                 createUser·p0.999:  12.174 ms/op
                 createUser·p0.9999: 14.116 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   2: 2.560 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  10.322 ms/op
                 createUser·p0.9999: 12.280 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   3: 2.594 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.301 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  7.715 ms/op
                 createUser·p0.9999: 10.431 ms/op
                 createUser·p1.00:   11.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372137
  mean =      2.578 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 176573 
    [ 2.500,  3.750) = 190345 
    [ 3.750,  5.000) = 4138 
    [ 5.000,  6.250) = 626 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.900 ms/op
     p(50.0000) =      2.642 ms/op
     p(90.0000) =      3.129 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      8.279 ms/op
     p(99.9900) =     13.644 ms/op
     p(99.9990) =     14.579 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 3.655 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.558 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
Iteration   1: 2.506 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  5.372 ms/op
                 existUser·p0.9999: 13.586 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.084 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   3.936 ms/op
                 existUser·p0.999:  9.175 ms/op
                 existUser·p0.9999: 16.924 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.992 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.080 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   3.929 ms/op
                 existUser·p0.999:  8.667 ms/op
                 existUser·p0.9999: 12.152 ms/op
                 existUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 380631
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 185394 
    [ 2.500,  3.750) = 190781 
    [ 3.750,  5.000) = 3457 
    [ 5.000,  6.250) = 520 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      7.920 ms/op
     p(99.9900) =     14.021 ms/op
     p(99.9990) =     17.406 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 3.879 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.674 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.596 ±(99.9%) 0.006 ms/op
Iteration   1: 2.565 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.969 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  12.359 ms/op
                 getUser·p0.9999: 14.312 ms/op
                 getUser·p1.00:   14.713 ms/op

Iteration   2: 2.621 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.893 ms/op
                 getUser·p0.50:   2.683 ms/op
                 getUser·p0.90:   3.166 ms/op
                 getUser·p0.95:   3.355 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  9.781 ms/op
                 getUser·p0.9999: 14.657 ms/op
                 getUser·p1.00:   15.221 ms/op

Iteration   3: 2.618 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   2.671 ms/op
                 getUser·p0.90:   3.199 ms/op
                 getUser·p0.95:   3.375 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.486 ms/op
                 getUser·p0.9999: 11.675 ms/op
                 getUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 368768
  mean =      2.601 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 174859 
    [ 2.500,  3.750) = 186238 
    [ 3.750,  5.000) = 5710 
    [ 5.000,  6.250) = 1348 
    [ 6.250,  7.500) = 184 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 79 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.158 ms/op
     p(95.0000) =      3.310 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.791 ms/op
     p(99.9900) =     14.320 ms/op
     p(99.9990) =     15.160 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 4.891 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.009 ms/op
Iteration   1: 3.118 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.515 ms/op
                 listUser·p0.50:   3.052 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.588 ms/op
                 listUser·p0.99:   5.956 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 12.173 ms/op
                 listUser·p1.00:   12.550 ms/op

Iteration   2: 3.072 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.943 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 11.718 ms/op
                 listUser·p1.00:   12.157 ms/op

Iteration   3: 3.068 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 10.462 ms/op
                 listUser·p1.00:   11.207 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310824
  mean =      3.086 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 79965 
    [ 2.500,  3.750) = 186113 
    [ 3.750,  5.000) = 36488 
    [ 5.000,  6.250) = 6527 
    [ 6.250,  7.500) = 910 
    [ 7.500,  8.750) = 269 
    [ 8.750, 10.000) = 231 
    [10.000, 11.250) = 156 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.522 ms/op
     p(99.9900) =     11.728 ms/op
     p(99.9990) =     12.499 ms/op
     p(99.9999) =     12.550 ms/op
    p(100.0000) =     12.550 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.424 ± 1.479  ops/ms
ClientPb.existUser                       thrpt       3  12.726 ± 1.501  ops/ms
ClientPb.getUser                         thrpt       3  12.353 ± 1.852  ops/ms
ClientPb.listUser                        thrpt       3  10.560 ± 1.752  ops/ms
ClientPb.createUser                       avgt       3   2.606 ± 0.540   ms/op
ClientPb.existUser                        avgt       3   2.520 ± 0.048   ms/op
ClientPb.getUser                          avgt       3   2.571 ± 0.180   ms/op
ClientPb.listUser                         avgt       3   3.057 ± 0.224   ms/op
ClientPb.createUser                     sample  372137   2.578 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.900           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.642           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.279           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.644           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.041           ms/op
ClientPb.existUser                      sample  380631   2.520 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.928           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.920           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.021           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.498           ms/op
ClientPb.getUser                        sample  368768   2.601 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.893           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.650           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.158           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.791           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.320           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.221           ms/op
ClientPb.listUser                       sample  310824   3.086 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.515           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.023           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.710           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.522           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.728           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.550           ms/op
