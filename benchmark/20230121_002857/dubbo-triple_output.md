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
# Warmup Iteration   1: 2.277 ops/ms
# Warmup Iteration   2: 5.181 ops/ms
# Warmup Iteration   3: 8.766 ops/ms
Iteration   1: 9.317 ops/ms
Iteration   2: 9.436 ops/ms
Iteration   3: 9.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.407 ±(99.9%) 1.470 ops/ms [Average]
  (min, avg, max) = (9.317, 9.407, 9.470), stdev = 0.081
  CI (99.9%): [7.937, 10.878] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.279 ops/ms
# Warmup Iteration   2: 8.781 ops/ms
# Warmup Iteration   3: 9.683 ops/ms
Iteration   1: 10.073 ops/ms
Iteration   2: 9.688 ops/ms
Iteration   3: 9.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.903 ±(99.9%) 3.587 ops/ms [Average]
  (min, avg, max) = (9.688, 9.903, 10.073), stdev = 0.197
  CI (99.9%): [6.316, 13.491] (assumes normal distribution)


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
# Warmup Iteration   1: 3.321 ops/ms
# Warmup Iteration   2: 8.728 ops/ms
# Warmup Iteration   3: 8.988 ops/ms
Iteration   1: 9.069 ops/ms
Iteration   2: 9.454 ops/ms
Iteration   3: 9.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.229 ±(99.9%) 3.657 ops/ms [Average]
  (min, avg, max) = (9.069, 9.229, 9.454), stdev = 0.200
  CI (99.9%): [5.572, 12.886] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.611 ops/ms
# Warmup Iteration   2: 7.086 ops/ms
# Warmup Iteration   3: 7.805 ops/ms
Iteration   1: 7.742 ops/ms
Iteration   2: 8.188 ops/ms
Iteration   3: 8.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.039 ±(99.9%) 4.702 ops/ms [Average]
  (min, avg, max) = (7.742, 8.039, 8.188), stdev = 0.258
  CI (99.9%): [3.337, 12.741] (assumes normal distribution)


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
# Warmup Iteration   1: 9.963 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
Iteration   1: 3.416 ±(99.9%) 0.006 ms/op
Iteration   2: 3.400 ±(99.9%) 0.006 ms/op
Iteration   3: 3.246 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.354 ±(99.9%) 1.713 ms/op [Average]
  (min, avg, max) = (3.246, 3.354, 3.416), stdev = 0.094
  CI (99.9%): [1.641, 5.067] (assumes normal distribution)


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
# Warmup Iteration   1: 8.335 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.004 ms/op
Iteration   1: 3.285 ±(99.9%) 0.004 ms/op
Iteration   2: 3.210 ±(99.9%) 0.004 ms/op
Iteration   3: 3.263 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.253 ±(99.9%) 0.705 ms/op [Average]
  (min, avg, max) = (3.210, 3.253, 3.285), stdev = 0.039
  CI (99.9%): [2.548, 3.958] (assumes normal distribution)


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
# Warmup Iteration   1: 9.290 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.411 ±(99.9%) 0.008 ms/op
Iteration   1: 3.326 ±(99.9%) 0.010 ms/op
Iteration   2: 3.561 ±(99.9%) 0.003 ms/op
Iteration   3: 3.335 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.407 ±(99.9%) 2.432 ms/op [Average]
  (min, avg, max) = (3.326, 3.407, 3.561), stdev = 0.133
  CI (99.9%): [0.976, 5.839] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.888 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.012 ms/op
Iteration   1: 3.930 ±(99.9%) 0.011 ms/op
Iteration   2: 3.897 ±(99.9%) 0.013 ms/op
Iteration   3: 3.965 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.931 ±(99.9%) 0.619 ms/op [Average]
  (min, avg, max) = (3.897, 3.931, 3.965), stdev = 0.034
  CI (99.9%): [3.312, 4.550] (assumes normal distribution)


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
# Warmup Iteration   1: 9.737 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.011 ms/op
Iteration   1: 3.324 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  17.041 ms/op
                 createUser·p0.9999: 24.272 ms/op
                 createUser·p1.00:   24.576 ms/op

Iteration   2: 3.332 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   5.471 ms/op
                 createUser·p0.999:  22.354 ms/op
                 createUser·p0.9999: 34.826 ms/op
                 createUser·p1.00:   35.783 ms/op

Iteration   3: 3.487 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.688 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  18.252 ms/op
                 createUser·p0.9999: 26.721 ms/op
                 createUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 284086
  mean =      3.379 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9643 
    [ 2.500,  5.000) = 268057 
    [ 5.000,  7.500) = 5320 
    [ 7.500, 10.000) = 618 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     18.243 ms/op
     p(99.9900) =     33.508 ms/op
     p(99.9990) =     35.662 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.505 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.339 ±(99.9%) 0.009 ms/op
Iteration   1: 3.252 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   5.691 ms/op
                 existUser·p0.999:  10.169 ms/op
                 existUser·p0.9999: 21.829 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   2: 3.219 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  8.757 ms/op
                 existUser·p0.9999: 24.412 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   3: 3.322 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.808 ms/op
                 existUser·p0.999:  19.573 ms/op
                 existUser·p0.9999: 24.844 ms/op
                 existUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293848
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9331 
    [ 2.500,  5.000) = 278954 
    [ 5.000,  7.500) = 4575 
    [ 7.500, 10.000) = 546 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 155 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     13.358 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     25.461 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


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
# Warmup Iteration   1: 9.383 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.777 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.489 ±(99.9%) 0.011 ms/op
Iteration   1: 3.560 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.749 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   5.587 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  17.887 ms/op
                 getUser·p0.9999: 21.267 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   2: 3.266 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.307 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.539 ms/op
                 getUser·p0.999:  9.372 ms/op
                 getUser·p0.9999: 21.896 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.457 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  10.934 ms/op
                 getUser·p0.9999: 32.145 ms/op
                 getUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280179
  mean =      3.423 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14934 
    [ 2.500,  5.000) = 254239 
    [ 5.000,  7.500) = 9868 
    [ 7.500, 10.000) = 770 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.832 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     32.538 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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
# Warmup Iteration   1: 9.254 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.012 ms/op
Iteration   1: 3.989 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  19.677 ms/op
                 listUser·p0.9999: 25.951 ms/op
                 listUser·p1.00:   26.771 ms/op

Iteration   2: 4.014 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 21.038 ms/op
                 listUser·p1.00:   21.561 ms/op

Iteration   3: 4.011 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  14.238 ms/op
                 listUser·p0.9999: 15.483 ms/op
                 listUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239520
  mean =      4.005 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 231111 
    [ 5.000,  7.500) = 6044 
    [ 7.500, 10.000) = 1635 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 340 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.463 ms/op
     p(99.9000) =     14.909 ms/op
     p(99.9900) =     24.609 ms/op
     p(99.9990) =     26.602 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.407 ± 1.470  ops/ms
ClientPb.existUser                       thrpt       3   9.903 ± 3.587  ops/ms
ClientPb.getUser                         thrpt       3   9.229 ± 3.657  ops/ms
ClientPb.listUser                        thrpt       3   8.039 ± 4.702  ops/ms
ClientPb.createUser                       avgt       3   3.354 ± 1.713   ms/op
ClientPb.existUser                        avgt       3   3.253 ± 0.705   ms/op
ClientPb.getUser                          avgt       3   3.407 ± 2.432   ms/op
ClientPb.listUser                         avgt       3   3.931 ± 0.619   ms/op
ClientPb.createUser                     sample  284086   3.379 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.096           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.325           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.857           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.243           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.508           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.783           ms/op
ClientPb.existUser                      sample  293848   3.263 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.788           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.170           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.358           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.281           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.461           ms/op
ClientPb.getUser                        sample  280179   3.423 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.163           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.297           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.653           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.832           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.238           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.212           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.735           ms/op
ClientPb.listUser                       sample  239520   4.005 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.163           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.463           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.909           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.609           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.771           ms/op
