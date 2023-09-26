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
# Warmup Iteration   1: 2.156 ops/ms
# Warmup Iteration   2: 5.756 ops/ms
# Warmup Iteration   3: 8.998 ops/ms
Iteration   1: 9.728 ops/ms
Iteration   2: 9.889 ops/ms
Iteration   3: 10.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.918 ±(99.9%) 3.740 ops/ms [Average]
  (min, avg, max) = (9.728, 9.918, 10.135), stdev = 0.205
  CI (99.9%): [6.178, 13.658] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.309 ops/ms
# Warmup Iteration   2: 8.360 ops/ms
# Warmup Iteration   3: 10.008 ops/ms
Iteration   1: 10.072 ops/ms
Iteration   2: 10.085 ops/ms
Iteration   3: 10.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.191 ±(99.9%) 3.553 ops/ms [Average]
  (min, avg, max) = (10.072, 10.191, 10.416), stdev = 0.195
  CI (99.9%): [6.637, 13.744] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.412 ops/ms
# Warmup Iteration   2: 9.428 ops/ms
# Warmup Iteration   3: 9.605 ops/ms
Iteration   1: 9.597 ops/ms
Iteration   2: 9.964 ops/ms
Iteration   3: 9.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.797 ±(99.9%) 3.385 ops/ms [Average]
  (min, avg, max) = (9.597, 9.797, 9.964), stdev = 0.186
  CI (99.9%): [6.413, 13.182] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.896 ops/ms
# Warmup Iteration   2: 7.553 ops/ms
# Warmup Iteration   3: 7.988 ops/ms
Iteration   1: 8.246 ops/ms
Iteration   2: 8.191 ops/ms
Iteration   3: 8.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.198 ±(99.9%) 0.827 ops/ms [Average]
  (min, avg, max) = (8.157, 8.198, 8.246), stdev = 0.045
  CI (99.9%): [7.371, 9.024] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.694 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.004 ms/op
Iteration   1: 3.257 ±(99.9%) 0.007 ms/op
Iteration   2: 3.333 ±(99.9%) 0.004 ms/op
Iteration   3: 3.344 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.312 ±(99.9%) 0.868 ms/op [Average]
  (min, avg, max) = (3.257, 3.312, 3.344), stdev = 0.048
  CI (99.9%): [2.444, 4.179] (assumes normal distribution)


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
# Warmup Iteration   1: 7.514 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.004 ms/op
Iteration   1: 3.133 ±(99.9%) 0.004 ms/op
Iteration   2: 3.116 ±(99.9%) 0.003 ms/op
Iteration   3: 3.068 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.106 ±(99.9%) 0.621 ms/op [Average]
  (min, avg, max) = (3.068, 3.106, 3.133), stdev = 0.034
  CI (99.9%): [2.485, 3.726] (assumes normal distribution)


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
# Warmup Iteration   1: 9.122 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.003 ms/op
Iteration   1: 3.267 ±(99.9%) 0.002 ms/op
Iteration   2: 3.271 ±(99.9%) 0.003 ms/op
Iteration   3: 3.212 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.250 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (3.212, 3.250, 3.271), stdev = 0.033
  CI (99.9%): [2.652, 3.847] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.380 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.003 ms/op
Iteration   1: 3.939 ±(99.9%) 0.003 ms/op
Iteration   2: 3.862 ±(99.9%) 0.005 ms/op
Iteration   3: 3.924 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.908 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (3.862, 3.908, 3.939), stdev = 0.041
  CI (99.9%): [3.156, 4.661] (assumes normal distribution)


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
# Warmup Iteration   1: 9.522 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.826 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.008 ms/op
Iteration   1: 3.264 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.176 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  16.400 ms/op
                 createUser·p0.9999: 21.502 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   2: 3.264 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.968 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  13.591 ms/op
                 createUser·p0.9999: 22.066 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   3: 3.290 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.128 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.005 ms/op
                 createUser·p0.999:  12.599 ms/op
                 createUser·p0.9999: 22.198 ms/op
                 createUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293308
  mean =      3.273 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14587 
    [ 2.500,  5.000) = 274641 
    [ 5.000,  7.500) = 3178 
    [ 7.500, 10.000) = 352 
    [10.000, 12.500) = 231 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     14.909 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     22.977 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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
# Warmup Iteration   1: 7.123 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.404 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.008 ms/op
Iteration   1: 3.203 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  11.424 ms/op
                 existUser·p0.9999: 21.433 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   2: 3.143 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  14.636 ms/op
                 existUser·p0.9999: 23.134 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   3: 3.240 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.444 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  10.982 ms/op
                 existUser·p0.9999: 21.467 ms/op
                 existUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300125
  mean =      3.195 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17748 
    [ 2.500,  5.000) = 276607 
    [ 5.000,  7.500) = 4978 
    [ 7.500, 10.000) = 364 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     12.270 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     23.724 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 8.594 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.504 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.008 ms/op
Iteration   1: 3.213 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  17.359 ms/op
                 getUser·p0.9999: 26.838 ms/op
                 getUser·p1.00:   27.197 ms/op

Iteration   2: 3.312 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  16.817 ms/op
                 getUser·p0.9999: 20.634 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   3: 3.252 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.321 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  10.813 ms/op
                 getUser·p0.9999: 21.316 ms/op
                 getUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294579
  mean =      3.259 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10127 
    [ 2.500,  5.000) = 279151 
    [ 5.000,  7.500) = 4259 
    [ 7.500, 10.000) = 478 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 173 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     25.511 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.209 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.173 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.011 ms/op
Iteration   1: 3.922 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.577 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 20.048 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   2: 3.838 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.795 ms/op
                 listUser·p0.9999: 16.663 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 3.839 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.081 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.324 ms/op
                 listUser·p0.999:  13.369 ms/op
                 listUser·p0.9999: 16.963 ms/op
                 listUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248279
  mean =      3.866 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 242310 
    [ 5.000,  7.500) = 4724 
    [ 7.500, 10.000) = 514 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 355 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.577 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.539 ms/op
     p(99.9000) =     13.856 ms/op
     p(99.9900) =     19.246 ms/op
     p(99.9990) =     20.861 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.918 ± 3.740  ops/ms
ClientPb.existUser                       thrpt       3  10.191 ± 3.553  ops/ms
ClientPb.getUser                         thrpt       3   9.797 ± 3.385  ops/ms
ClientPb.listUser                        thrpt       3   8.198 ± 0.827  ops/ms
ClientPb.createUser                       avgt       3   3.312 ± 0.868   ms/op
ClientPb.existUser                        avgt       3   3.106 ± 0.621   ms/op
ClientPb.getUser                          avgt       3   3.250 ± 0.598   ms/op
ClientPb.listUser                         avgt       3   3.908 ± 0.753   ms/op
ClientPb.createUser                     sample  293308   3.273 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.968           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.219           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.936           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.909           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.053           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.233           ms/op
ClientPb.existUser                      sample  300125   3.195 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.017           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.817           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.890           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.270           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.675           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.183           ms/op
ClientPb.getUser                        sample  294579   3.259 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.253           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.613           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.825           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.072           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.511           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.197           ms/op
ClientPb.listUser                       sample  248279   3.866 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.577           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.768           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.539           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.856           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.246           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.168           ms/op
