# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.576 ops/ms
# Warmup Iteration   2: 6.065 ops/ms
# Warmup Iteration   3: 8.963 ops/ms
Iteration   1: 9.707 ops/ms
Iteration   2: 9.999 ops/ms
Iteration   3: 9.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.883 ±(99.9%) 2.830 ops/ms [Average]
  (min, avg, max) = (9.707, 9.883, 9.999), stdev = 0.155
  CI (99.9%): [7.053, 12.714] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.288 ops/ms
# Warmup Iteration   2: 9.020 ops/ms
# Warmup Iteration   3: 9.663 ops/ms
Iteration   1: 10.150 ops/ms
Iteration   2: 9.591 ops/ms
Iteration   3: 10.187 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.976 ±(99.9%) 6.091 ops/ms [Average]
  (min, avg, max) = (9.591, 9.976, 10.187), stdev = 0.334
  CI (99.9%): [3.885, 16.067] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.455 ops/ms
# Warmup Iteration   2: 9.224 ops/ms
# Warmup Iteration   3: 9.730 ops/ms
Iteration   1: 9.930 ops/ms
Iteration   2: 9.934 ops/ms
Iteration   3: 9.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.833 ±(99.9%) 3.138 ops/ms [Average]
  (min, avg, max) = (9.634, 9.833, 9.934), stdev = 0.172
  CI (99.9%): [6.694, 12.971] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.035 ops/ms
# Warmup Iteration   2: 7.480 ops/ms
# Warmup Iteration   3: 8.209 ops/ms
Iteration   1: 8.621 ops/ms
Iteration   2: 8.563 ops/ms
Iteration   3: 8.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.600 ±(99.9%) 0.586 ops/ms [Average]
  (min, avg, max) = (8.563, 8.600, 8.621), stdev = 0.032
  CI (99.9%): [8.014, 9.186] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.235 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.007 ms/op
Iteration   1: 3.135 ±(99.9%) 0.002 ms/op
Iteration   2: 3.303 ±(99.9%) 0.005 ms/op
Iteration   3: 3.107 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.181 ±(99.9%) 1.932 ms/op [Average]
  (min, avg, max) = (3.107, 3.181, 3.303), stdev = 0.106
  CI (99.9%): [1.250, 5.113] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.562 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.450 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.003 ms/op
Iteration   1: 3.116 ±(99.9%) 0.006 ms/op
Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
Iteration   3: 3.052 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.082 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (3.052, 3.082, 3.116), stdev = 0.032
  CI (99.9%): [2.492, 3.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.120 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.005 ms/op
Iteration   1: 3.313 ±(99.9%) 0.005 ms/op
Iteration   2: 3.214 ±(99.9%) 0.006 ms/op
Iteration   3: 3.260 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.263 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (3.214, 3.263, 3.313), stdev = 0.049
  CI (99.9%): [2.366, 4.159] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.972 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.005 ms/op
Iteration   1: 3.824 ±(99.9%) 0.005 ms/op
Iteration   2: 3.798 ±(99.9%) 0.008 ms/op
Iteration   3: 3.757 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.793 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (3.757, 3.793, 3.824), stdev = 0.034
  CI (99.9%): [3.173, 4.413] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.195 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.009 ms/op
Iteration   1: 3.142 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  18.016 ms/op
                 createUser·p0.9999: 23.876 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   2: 3.208 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.315 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  14.320 ms/op
                 createUser·p0.9999: 22.647 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   3: 3.210 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.743 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  15.007 ms/op
                 createUser·p0.9999: 25.859 ms/op
                 createUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300922
  mean =      3.186 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17625 
    [ 2.500,  5.000) = 277609 
    [ 5.000,  7.500) = 4808 
    [ 7.500, 10.000) = 416 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      5.520 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     24.850 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.139 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.314 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.049 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  8.719 ms/op
                 existUser·p0.9999: 20.956 ms/op
                 existUser·p1.00:   21.496 ms/op

Iteration   2: 3.097 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.112 ms/op
                 existUser·p0.999:  11.975 ms/op
                 existUser·p0.9999: 22.807 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  14.698 ms/op
                 existUser·p0.9999: 22.040 ms/op
                 existUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308888
  mean =      3.107 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11192 
    [ 2.500,  5.000) = 293219 
    [ 5.000,  7.500) = 3727 
    [ 7.500, 10.000) = 309 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     21.907 ms/op
     p(99.9990) =     23.953 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.301 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.454 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.009 ms/op
Iteration   1: 3.314 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.341 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   7.038 ms/op
                 getUser·p0.999:  18.022 ms/op
                 getUser·p0.9999: 21.191 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   2: 3.218 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.462 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  11.396 ms/op
                 getUser·p0.9999: 31.397 ms/op
                 getUser·p1.00:   32.014 ms/op

Iteration   3: 3.223 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.251 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  11.089 ms/op
                 getUser·p0.9999: 20.352 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295108
  mean =      3.251 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9338 
    [ 2.500,  5.000) = 277577 
    [ 5.000,  7.500) = 6950 
    [ 7.500, 10.000) = 804 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      6.610 ms/op
     p(99.9000) =     15.771 ms/op
     p(99.9900) =     30.211 ms/op
     p(99.9990) =     31.949 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.881 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.321 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.011 ms/op
Iteration   1: 3.745 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 21.475 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   2: 3.918 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  14.885 ms/op
                 listUser·p0.9999: 17.525 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 3.837 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  12.905 ms/op
                 listUser·p0.9999: 19.410 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250372
  mean =      3.832 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 241002 
    [ 5.000,  7.500) = 7296 
    [ 7.500, 10.000) = 1378 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.612 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     15.346 ms/op
     p(99.9900) =     20.301 ms/op
     p(99.9990) =     22.086 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.883 ± 2.830  ops/ms
ClientPb.existUser                       thrpt       3   9.976 ± 6.091  ops/ms
ClientPb.getUser                         thrpt       3   9.833 ± 3.138  ops/ms
ClientPb.listUser                        thrpt       3   8.600 ± 0.586  ops/ms
ClientPb.createUser                       avgt       3   3.181 ± 1.932   ms/op
ClientPb.existUser                        avgt       3   3.082 ± 0.590   ms/op
ClientPb.getUser                          avgt       3   3.263 ± 0.897   ms/op
ClientPb.listUser                         avgt       3   3.793 ± 0.620   ms/op
ClientPb.createUser                     sample  300922   3.186 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.315           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.531           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.520           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.237           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.850           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.509           ms/op
ClientPb.existUser                      sample  308888   3.107 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.022           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.008           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.907           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.117           ms/op
ClientPb.getUser                        sample  295108   3.251 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.251           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.559           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.610           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.771           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.211           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.014           ms/op
ClientPb.listUser                       sample  250372   3.832 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.612           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.160           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.346           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.301           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.905           ms/op
