# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.419 ops/ms
# Warmup Iteration   2: 5.875 ops/ms
# Warmup Iteration   3: 8.756 ops/ms
Iteration   1: 9.613 ops/ms
Iteration   2: 9.653 ops/ms
Iteration   3: 9.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.581 ±(99.9%) 1.688 ops/ms [Average]
  (min, avg, max) = (9.476, 9.581, 9.653), stdev = 0.093
  CI (99.9%): [7.893, 11.269] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.346 ops/ms
# Warmup Iteration   2: 9.197 ops/ms
# Warmup Iteration   3: 10.208 ops/ms
Iteration   1: 10.085 ops/ms
Iteration   2: 10.043 ops/ms
Iteration   3: 9.857 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.995 ±(99.9%) 2.209 ops/ms [Average]
  (min, avg, max) = (9.857, 9.995, 10.085), stdev = 0.121
  CI (99.9%): [7.786, 12.205] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.269 ops/ms
# Warmup Iteration   2: 9.047 ops/ms
# Warmup Iteration   3: 9.527 ops/ms
Iteration   1: 9.596 ops/ms
Iteration   2: 9.626 ops/ms
Iteration   3: 9.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.618 ±(99.9%) 0.356 ops/ms [Average]
  (min, avg, max) = (9.596, 9.618, 9.632), stdev = 0.020
  CI (99.9%): [9.262, 9.974] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.014 ops/ms
# Warmup Iteration   2: 7.684 ops/ms
# Warmup Iteration   3: 8.070 ops/ms
Iteration   1: 8.229 ops/ms
Iteration   2: 8.027 ops/ms
Iteration   3: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.152 ±(99.9%) 1.995 ops/ms [Average]
  (min, avg, max) = (8.027, 8.152, 8.229), stdev = 0.109
  CI (99.9%): [6.157, 10.148] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.800 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.646 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.004 ms/op
Iteration   1: 3.358 ±(99.9%) 0.005 ms/op
Iteration   2: 3.378 ±(99.9%) 0.005 ms/op
Iteration   3: 3.308 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.348 ±(99.9%) 0.655 ms/op [Average]
  (min, avg, max) = (3.308, 3.348, 3.378), stdev = 0.036
  CI (99.9%): [2.693, 4.004] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.048 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.003 ms/op
Iteration   1: 3.197 ±(99.9%) 0.003 ms/op
Iteration   2: 3.097 ±(99.9%) 0.004 ms/op
Iteration   3: 3.211 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.168 ±(99.9%) 1.129 ms/op [Average]
  (min, avg, max) = (3.097, 3.168, 3.211), stdev = 0.062
  CI (99.9%): [2.039, 4.297] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.519 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.004 ms/op
Iteration   1: 3.382 ±(99.9%) 0.002 ms/op
Iteration   2: 3.357 ±(99.9%) 0.005 ms/op
Iteration   3: 3.285 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.341 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.285, 3.341, 3.382), stdev = 0.051
  CI (99.9%): [2.417, 4.266] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.838 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.005 ms/op
Iteration   1: 3.894 ±(99.9%) 0.006 ms/op
Iteration   2: 3.929 ±(99.9%) 0.004 ms/op
Iteration   3: 3.857 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.893 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (3.857, 3.893, 3.929), stdev = 0.036
  CI (99.9%): [3.237, 4.550] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.119 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.010 ms/op
Iteration   1: 3.408 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.971 ms/op
                 createUser·p0.999:  17.859 ms/op
                 createUser·p0.9999: 21.647 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   2: 3.325 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  19.439 ms/op
                 createUser·p0.9999: 24.884 ms/op
                 createUser·p1.00:   26.116 ms/op

Iteration   3: 3.330 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  17.332 ms/op
                 createUser·p0.9999: 26.555 ms/op
                 createUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286041
  mean =      3.354 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12867 
    [ 2.500,  5.000) = 265602 
    [ 5.000,  7.500) = 6083 
    [ 7.500, 10.000) = 912 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      6.820 ms/op
     p(99.9000) =     17.498 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     27.600 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.836 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.009 ms/op
Iteration   1: 3.267 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   6.433 ms/op
                 existUser·p0.999:  17.499 ms/op
                 existUser·p0.9999: 20.900 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   2: 3.298 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.153 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  13.844 ms/op
                 existUser·p0.9999: 22.774 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   3: 3.205 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  19.056 ms/op
                 existUser·p0.9999: 25.527 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294746
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15403 
    [ 2.500,  5.000) = 271681 
    [ 5.000,  7.500) = 6333 
    [ 7.500, 10.000) = 742 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     15.393 ms/op
     p(99.9900) =     24.266 ms/op
     p(99.9990) =     26.904 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.596 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.798 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.011 ms/op
Iteration   1: 3.419 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.526 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   7.670 ms/op
                 getUser·p0.999:  19.514 ms/op
                 getUser·p0.9999: 22.271 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   2: 3.200 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  17.692 ms/op
                 getUser·p0.9999: 23.527 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   3: 3.330 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.316 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.116 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  16.089 ms/op
                 getUser·p0.9999: 21.476 ms/op
                 getUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289443
  mean =      3.314 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11540 
    [ 2.500,  5.000) = 267537 
    [ 5.000,  7.500) = 8679 
    [ 7.500, 10.000) = 801 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 157 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.316 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     17.320 ms/op
     p(99.9900) =     22.615 ms/op
     p(99.9990) =     23.843 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.873 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.272 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.012 ms/op
Iteration   1: 4.022 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.722 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.904 ms/op
                 listUser·p0.999:  16.235 ms/op
                 listUser·p0.9999: 20.418 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   2: 4.054 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  14.582 ms/op
                 listUser·p0.9999: 22.125 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   3: 3.890 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  13.595 ms/op
                 listUser·p0.9999: 23.666 ms/op
                 listUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240657
  mean =      3.987 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 88 
    [ 2.500,  5.000) = 231369 
    [ 5.000,  7.500) = 5973 
    [ 7.500, 10.000) = 2251 
    [10.000, 12.500) = 355 
    [12.500, 15.000) = 434 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     14.631 ms/op
     p(99.9900) =     22.049 ms/op
     p(99.9990) =     25.662 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.581 ± 1.688  ops/ms
ClientPb.existUser                       thrpt       3   9.995 ± 2.209  ops/ms
ClientPb.getUser                         thrpt       3   9.618 ± 0.356  ops/ms
ClientPb.listUser                        thrpt       3   8.152 ± 1.995  ops/ms
ClientPb.createUser                       avgt       3   3.348 ± 0.655   ms/op
ClientPb.existUser                        avgt       3   3.168 ± 1.129   ms/op
ClientPb.getUser                          avgt       3   3.341 ± 0.925   ms/op
ClientPb.listUser                         avgt       3   3.893 ± 0.657   ms/op
ClientPb.createUser                     sample  286041   3.354 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.983           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.129           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.820           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.498           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.002           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.017           ms/op
ClientPb.existUser                      sample  294746   3.256 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.034           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.166           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.969           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.504           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.393           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.266           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.951           ms/op
ClientPb.getUser                        sample  289443   3.314 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.316           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.320           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.615           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.052           ms/op
ClientPb.listUser                       sample  240657   3.987 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.524           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.830           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.864           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.631           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.049           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.788           ms/op
