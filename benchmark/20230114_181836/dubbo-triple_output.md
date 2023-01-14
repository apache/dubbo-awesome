# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.684 ops/ms
# Warmup Iteration   2: 6.523 ops/ms
# Warmup Iteration   3: 9.394 ops/ms
Iteration   1: 10.160 ops/ms
Iteration   2: 9.875 ops/ms
Iteration   3: 9.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.986 ±(99.9%) 2.779 ops/ms [Average]
  (min, avg, max) = (9.875, 9.986, 10.160), stdev = 0.152
  CI (99.9%): [7.207, 12.765] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.720 ops/ms
# Warmup Iteration   2: 9.543 ops/ms
# Warmup Iteration   3: 10.359 ops/ms
Iteration   1: 10.227 ops/ms
Iteration   2: 10.448 ops/ms
Iteration   3: 10.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.422 ±(99.9%) 3.329 ops/ms [Average]
  (min, avg, max) = (10.227, 10.422, 10.589), stdev = 0.182
  CI (99.9%): [7.092, 13.751] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.841 ops/ms
# Warmup Iteration   2: 8.857 ops/ms
# Warmup Iteration   3: 9.815 ops/ms
Iteration   1: 10.167 ops/ms
Iteration   2: 10.311 ops/ms
Iteration   3: 10.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.218 ±(99.9%) 1.469 ops/ms [Average]
  (min, avg, max) = (10.167, 10.218, 10.311), stdev = 0.080
  CI (99.9%): [8.750, 11.687] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.484 ops/ms
# Warmup Iteration   2: 7.665 ops/ms
# Warmup Iteration   3: 8.422 ops/ms
Iteration   1: 8.529 ops/ms
Iteration   2: 8.329 ops/ms
Iteration   3: 8.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.510 ±(99.9%) 3.155 ops/ms [Average]
  (min, avg, max) = (8.329, 8.510, 8.673), stdev = 0.173
  CI (99.9%): [5.355, 11.665] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.733 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.410 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.002 ms/op
Iteration   1: 3.152 ±(99.9%) 0.003 ms/op
Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
Iteration   3: 3.171 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.170 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (3.152, 3.170, 3.186), stdev = 0.017
  CI (99.9%): [2.859, 3.480] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 6.968 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 3.168 ±(99.9%) 0.001 ms/op
Iteration   2: 3.047 ±(99.9%) 0.005 ms/op
Iteration   3: 3.144 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.119 ±(99.9%) 1.169 ms/op [Average]
  (min, avg, max) = (3.047, 3.119, 3.168), stdev = 0.064
  CI (99.9%): [1.951, 4.288] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.180 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.425 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.002 ms/op
Iteration   1: 3.266 ±(99.9%) 0.003 ms/op
Iteration   2: 3.102 ±(99.9%) 0.002 ms/op
Iteration   3: 3.070 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.146 ±(99.9%) 1.923 ms/op [Average]
  (min, avg, max) = (3.070, 3.146, 3.266), stdev = 0.105
  CI (99.9%): [1.223, 5.069] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.509 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.006 ms/op
Iteration   1: 3.622 ±(99.9%) 0.010 ms/op
Iteration   2: 3.923 ±(99.9%) 0.010 ms/op
Iteration   3: 3.541 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.695 ±(99.9%) 3.674 ms/op [Average]
  (min, avg, max) = (3.541, 3.695, 3.923), stdev = 0.201
  CI (99.9%): [0.021, 7.369] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.550 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.008 ms/op
Iteration   1: 3.112 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  9.708 ms/op
                 createUser·p0.9999: 19.946 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  19.324 ms/op
                 createUser·p0.9999: 22.438 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  11.008 ms/op
                 createUser·p0.9999: 19.634 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307719
  mean =      3.117 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15779 
    [ 2.500,  5.000) = 287701 
    [ 5.000,  7.500) = 3599 
    [ 7.500, 10.000) = 301 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 177 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     14.123 ms/op
     p(99.9900) =     21.453 ms/op
     p(99.9990) =     22.870 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.650 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
Iteration   1: 3.203 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.284 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  10.127 ms/op
                 existUser·p0.9999: 25.265 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.071 ms/op
                 existUser·p0.999:  8.768 ms/op
                 existUser·p0.9999: 23.985 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   3: 3.116 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.310 ms/op
                 existUser·p0.99:   5.014 ms/op
                 existUser·p0.999:  8.634 ms/op
                 existUser·p0.9999: 25.199 ms/op
                 existUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304405
  mean =      3.153 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37057 
    [ 2.500,  5.000) = 263080 
    [ 5.000,  7.500) = 3700 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.284 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =      9.686 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     26.082 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.440 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.010 ms/op
Iteration   1: 3.239 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  16.084 ms/op
                 getUser·p0.9999: 21.303 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   2: 3.229 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.292 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  19.822 ms/op
                 getUser·p0.9999: 27.495 ms/op
                 getUser·p1.00:   29.655 ms/op

Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  10.289 ms/op
                 getUser·p0.9999: 24.542 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298261
  mean =      3.217 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17626 
    [ 2.500,  5.000) = 271122 
    [ 5.000,  7.500) = 8567 
    [ 7.500, 10.000) = 507 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     25.484 ms/op
     p(99.9990) =     27.746 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.809 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.010 ms/op
Iteration   1: 3.731 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  17.091 ms/op
                 listUser·p0.9999: 22.420 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 3.615 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   1.335 ms/op
                 listUser·p0.50:   3.514 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.141 ms/op
                 listUser·p0.99:   6.382 ms/op
                 listUser·p0.999:  12.894 ms/op
                 listUser·p0.9999: 13.779 ms/op
                 listUser·p1.00:   13.844 ms/op

Iteration   3: 3.632 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   3.850 ms/op
                 listUser·p0.95:   4.153 ms/op
                 listUser·p0.99:   6.275 ms/op
                 listUser·p0.999:  13.386 ms/op
                 listUser·p0.9999: 17.210 ms/op
                 listUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 262024
  mean =      3.659 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 256562 
    [ 5.000,  7.500) = 3725 
    [ 7.500, 10.000) = 821 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     20.100 ms/op
     p(99.9990) =     23.048 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.986 ± 2.779  ops/ms
ClientPb.existUser                       thrpt       3  10.422 ± 3.329  ops/ms
ClientPb.getUser                         thrpt       3  10.218 ± 1.469  ops/ms
ClientPb.listUser                        thrpt       3   8.510 ± 3.155  ops/ms
ClientPb.createUser                       avgt       3   3.170 ± 0.311   ms/op
ClientPb.existUser                        avgt       3   3.119 ± 1.169   ms/op
ClientPb.getUser                          avgt       3   3.146 ± 1.923   ms/op
ClientPb.listUser                         avgt       3   3.695 ± 3.674   ms/op
ClientPb.createUser                     sample  307719   3.117 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.845           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.027           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.539           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.251           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.123           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.453           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.101           ms/op
ClientPb.existUser                      sample  304405   3.153 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.284           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.686           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.100           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.345           ms/op
ClientPb.getUser                        sample  298261   3.217 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.192           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.617           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.007           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.484           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.655           ms/op
ClientPb.listUser                       sample  262024   3.659 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.335           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.584           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.961           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.157           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.595           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.139           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.100           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.364           ms/op
