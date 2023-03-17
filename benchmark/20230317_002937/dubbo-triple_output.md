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
# Warmup Iteration   1: 2.698 ops/ms
# Warmup Iteration   2: 6.431 ops/ms
# Warmup Iteration   3: 9.401 ops/ms
Iteration   1: 9.733 ops/ms
Iteration   2: 9.988 ops/ms
Iteration   3: 10.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.941 ±(99.9%) 3.460 ops/ms [Average]
  (min, avg, max) = (9.733, 9.941, 10.103), stdev = 0.190
  CI (99.9%): [6.482, 13.401] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.962 ops/ms
# Warmup Iteration   2: 9.689 ops/ms
# Warmup Iteration   3: 10.129 ops/ms
Iteration   1: 10.334 ops/ms
Iteration   2: 10.632 ops/ms
Iteration   3: 10.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.545 ±(99.9%) 3.352 ops/ms [Average]
  (min, avg, max) = (10.334, 10.545, 10.669), stdev = 0.184
  CI (99.9%): [7.193, 13.897] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.835 ops/ms
# Warmup Iteration   2: 9.220 ops/ms
# Warmup Iteration   3: 9.705 ops/ms
Iteration   1: 9.971 ops/ms
Iteration   2: 10.006 ops/ms
Iteration   3: 10.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.111 ±(99.9%) 3.898 ops/ms [Average]
  (min, avg, max) = (9.971, 10.111, 10.357), stdev = 0.214
  CI (99.9%): [6.213, 14.009] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 3.412 ops/ms
# Warmup Iteration   2: 7.857 ops/ms
# Warmup Iteration   3: 8.306 ops/ms
Iteration   1: 8.581 ops/ms
Iteration   2: 8.527 ops/ms
Iteration   3: 8.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.596 ±(99.9%) 1.410 ops/ms [Average]
  (min, avg, max) = (8.527, 8.596, 8.679), stdev = 0.077
  CI (99.9%): [7.186, 10.006] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.327 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.207 ±(99.9%) 0.003 ms/op
Iteration   1: 3.174 ±(99.9%) 0.002 ms/op
Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
Iteration   3: 3.056 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.116 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (3.056, 3.116, 3.174), stdev = 0.059
  CI (99.9%): [2.036, 4.195] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.062 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.065 ±(99.9%) 0.005 ms/op
Iteration   2: 3.048 ±(99.9%) 0.007 ms/op
Iteration   3: 2.993 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.035 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (2.993, 3.035, 3.065), stdev = 0.038
  CI (99.9%): [2.346, 3.723] (assumes normal distribution)


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
# Warmup Iteration   1: 6.721 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.408 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.003 ms/op
Iteration   1: 3.253 ±(99.9%) 0.003 ms/op
Iteration   2: 3.041 ±(99.9%) 0.005 ms/op
Iteration   3: 3.203 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.166 ±(99.9%) 2.016 ms/op [Average]
  (min, avg, max) = (3.041, 3.166, 3.253), stdev = 0.111
  CI (99.9%): [1.150, 5.182] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.717 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.006 ms/op
Iteration   1: 3.623 ±(99.9%) 0.007 ms/op
Iteration   2: 3.659 ±(99.9%) 0.006 ms/op
Iteration   3: 3.671 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.651 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (3.623, 3.651, 3.671), stdev = 0.025
  CI (99.9%): [3.197, 4.105] (assumes normal distribution)


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
# Warmup Iteration   1: 7.870 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.803 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.317 ±(99.9%) 0.014 ms/op
Iteration   1: 3.321 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  21.463 ms/op
                 createUser·p0.9999: 26.652 ms/op
                 createUser·p1.00:   26.935 ms/op

Iteration   2: 3.200 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.415 ms/op
                 createUser·p0.999:  12.809 ms/op
                 createUser·p0.9999: 23.331 ms/op
                 createUser·p1.00:   24.248 ms/op

Iteration   3: 3.185 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  13.940 ms/op
                 createUser·p0.9999: 26.377 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296684
  mean =      3.234 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16846 
    [ 2.500,  5.000) = 274010 
    [ 5.000,  7.500) = 4862 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 45 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     26.247 ms/op
     p(99.9990) =     27.227 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 7.249 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.372 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
Iteration   1: 3.074 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  11.645 ms/op
                 existUser·p0.9999: 24.418 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   2: 3.265 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.520 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  12.757 ms/op
                 existUser·p0.9999: 22.387 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   3: 3.072 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  13.661 ms/op
                 existUser·p0.9999: 22.577 ms/op
                 existUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306353
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23334 
    [ 2.500,  5.000) = 277890 
    [ 5.000,  7.500) = 4440 
    [ 7.500, 10.000) = 334 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     23.682 ms/op
     p(99.9990) =     26.372 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 8.217 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
Iteration   1: 3.168 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.153 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  18.318 ms/op
                 getUser·p0.9999: 21.201 ms/op
                 getUser·p1.00:   22.053 ms/op

Iteration   2: 3.228 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.628 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  12.930 ms/op
                 getUser·p0.9999: 27.364 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   3: 3.375 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.806 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  13.844 ms/op
                 getUser·p0.9999: 23.020 ms/op
                 getUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294912
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13427 
    [ 2.500,  5.000) = 274631 
    [ 5.000,  7.500) = 5681 
    [ 7.500, 10.000) = 702 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     16.695 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     28.194 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 9.830 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.348 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.012 ms/op
Iteration   1: 3.918 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  16.206 ms/op
                 listUser·p0.9999: 22.474 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   2: 3.787 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.157 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  11.821 ms/op
                 listUser·p0.9999: 15.385 ms/op
                 listUser·p1.00:   15.434 ms/op

Iteration   3: 3.876 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  13.950 ms/op
                 listUser·p0.9999: 15.647 ms/op
                 listUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248618
  mean =      3.860 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49 
    [ 2.500,  5.000) = 238581 
    [ 5.000,  7.500) = 7292 
    [ 7.500, 10.000) = 1933 
    [10.000, 12.500) = 391 
    [12.500, 15.000) = 203 
    [15.000, 17.500) = 100 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     22.890 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.941 ± 3.460  ops/ms
ClientPb.existUser                       thrpt       3  10.545 ± 3.352  ops/ms
ClientPb.getUser                         thrpt       3  10.111 ± 3.898  ops/ms
ClientPb.listUser                        thrpt       3   8.596 ± 1.410  ops/ms
ClientPb.createUser                       avgt       3   3.116 ± 1.080   ms/op
ClientPb.existUser                        avgt       3   3.035 ± 0.689   ms/op
ClientPb.getUser                          avgt       3   3.166 ± 2.016   ms/op
ClientPb.listUser                         avgt       3   3.651 ± 0.454   ms/op
ClientPb.createUser                     sample  296684   3.234 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.169           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.990           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.247           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.295           ms/op
ClientPb.existUser                      sample  306353   3.134 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.043           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.517           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.682           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.477           ms/op
ClientPb.getUser                        sample  294912   3.255 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.153           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.153           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.038           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.695           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.280           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.098           ms/op
ClientPb.listUser                       sample  248618   3.860 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.720           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.707           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.610           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.533           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.725           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.560           ms/op
