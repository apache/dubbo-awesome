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
# Warmup Iteration   1: 2.440 ops/ms
# Warmup Iteration   2: 5.628 ops/ms
# Warmup Iteration   3: 8.790 ops/ms
Iteration   1: 9.709 ops/ms
Iteration   2: 9.840 ops/ms
Iteration   3: 9.495 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.681 ±(99.9%) 3.175 ops/ms [Average]
  (min, avg, max) = (9.495, 9.681, 9.840), stdev = 0.174
  CI (99.9%): [6.507, 12.856] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.846 ops/ms
# Warmup Iteration   2: 8.883 ops/ms
# Warmup Iteration   3: 10.170 ops/ms
Iteration   1: 10.441 ops/ms
Iteration   2: 10.465 ops/ms
Iteration   3: 10.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.334 ±(99.9%) 3.757 ops/ms [Average]
  (min, avg, max) = (10.097, 10.334, 10.465), stdev = 0.206
  CI (99.9%): [6.577, 14.092] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.130 ops/ms
# Warmup Iteration   2: 8.649 ops/ms
# Warmup Iteration   3: 9.458 ops/ms
Iteration   1: 9.521 ops/ms
Iteration   2: 9.798 ops/ms
Iteration   3: 9.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.688 ±(99.9%) 2.677 ops/ms [Average]
  (min, avg, max) = (9.521, 9.688, 9.798), stdev = 0.147
  CI (99.9%): [7.011, 12.365] (assumes normal distribution)


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
# Warmup Iteration   1: 3.407 ops/ms
# Warmup Iteration   2: 7.539 ops/ms
# Warmup Iteration   3: 8.292 ops/ms
Iteration   1: 7.919 ops/ms
Iteration   2: 8.155 ops/ms
Iteration   3: 8.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.173 ±(99.9%) 4.824 ops/ms [Average]
  (min, avg, max) = (7.919, 8.173, 8.446), stdev = 0.264
  CI (99.9%): [3.349, 12.998] (assumes normal distribution)


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
# Warmup Iteration   1: 9.525 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.005 ms/op
Iteration   1: 3.388 ±(99.9%) 0.004 ms/op
Iteration   2: 3.239 ±(99.9%) 0.007 ms/op
Iteration   3: 3.258 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.295 ±(99.9%) 1.481 ms/op [Average]
  (min, avg, max) = (3.239, 3.295, 3.388), stdev = 0.081
  CI (99.9%): [1.814, 4.777] (assumes normal distribution)


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
# Warmup Iteration   1: 7.815 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.006 ms/op
Iteration   1: 3.217 ±(99.9%) 0.008 ms/op
Iteration   2: 3.144 ±(99.9%) 0.005 ms/op
Iteration   3: 3.030 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.130 ±(99.9%) 1.726 ms/op [Average]
  (min, avg, max) = (3.030, 3.130, 3.217), stdev = 0.095
  CI (99.9%): [1.404, 4.857] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.717 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.003 ms/op
Iteration   1: 3.226 ±(99.9%) 0.003 ms/op
Iteration   2: 3.280 ±(99.9%) 0.004 ms/op
Iteration   3: 3.267 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.258 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (3.226, 3.258, 3.280), stdev = 0.028
  CI (99.9%): [2.745, 3.771] (assumes normal distribution)


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
# Warmup Iteration   1: 9.145 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.007 ms/op
Iteration   1: 3.843 ±(99.9%) 0.006 ms/op
Iteration   2: 3.823 ±(99.9%) 0.003 ms/op
Iteration   3: 3.789 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.818 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (3.789, 3.818, 3.843), stdev = 0.028
  CI (99.9%): [3.315, 4.322] (assumes normal distribution)


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
# Warmup Iteration   1: 7.733 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.012 ms/op
Iteration   1: 3.270 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.368 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  12.829 ms/op
                 createUser·p0.9999: 24.500 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   2: 3.453 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  19.152 ms/op
                 createUser·p0.9999: 26.804 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   3: 3.212 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.599 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  15.385 ms/op
                 createUser·p0.9999: 28.641 ms/op
                 createUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289731
  mean =      3.309 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19934 
    [ 2.500,  5.000) = 262803 
    [ 5.000,  7.500) = 5363 
    [ 7.500, 10.000) = 1139 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     29.531 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 6.949 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.433 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.008 ms/op
Iteration   1: 3.182 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   4.021 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  10.516 ms/op
                 existUser·p0.9999: 18.806 ms/op
                 existUser·p1.00:   19.366 ms/op

Iteration   2: 3.160 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   6.767 ms/op
                 existUser·p0.999:  15.876 ms/op
                 existUser·p0.9999: 20.493 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   3: 3.344 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  13.779 ms/op
                 existUser·p0.9999: 38.751 ms/op
                 existUser·p1.00:   40.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297285
  mean =      3.227 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 288633 
    [ 5.000, 10.000) = 8034 
    [10.000, 15.000) = 354 
    [15.000, 20.000) = 193 
    [20.000, 25.000) = 39 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      4.035 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     37.159 ms/op
     p(99.9990) =     39.214 ms/op
     p(99.9999) =     40.436 ms/op
    p(100.0000) =     40.436 ms/op


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
# Warmup Iteration   1: 7.817 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.488 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.009 ms/op
Iteration   1: 3.292 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   5.276 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  12.656 ms/op
                 getUser·p0.9999: 20.564 ms/op
                 getUser·p1.00:   21.103 ms/op

Iteration   2: 3.258 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  12.386 ms/op
                 getUser·p0.9999: 22.777 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   3: 3.303 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.595 ms/op
                 getUser·p0.999:  11.586 ms/op
                 getUser·p0.9999: 22.752 ms/op
                 getUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292214
  mean =      3.284 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10812 
    [ 2.500,  5.000) = 270493 
    [ 5.000,  7.500) = 9259 
    [ 7.500, 10.000) = 1276 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     12.383 ms/op
     p(99.9900) =     22.046 ms/op
     p(99.9990) =     23.813 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.873 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.012 ms/op
Iteration   1: 3.904 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.906 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  17.538 ms/op
                 listUser·p0.9999: 23.083 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 3.808 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.133 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  15.925 ms/op
                 listUser·p0.9999: 19.451 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   3: 3.763 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.091 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  12.665 ms/op
                 listUser·p0.9999: 15.245 ms/op
                 listUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250981
  mean =      3.824 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95 
    [ 2.500,  5.000) = 240547 
    [ 5.000,  7.500) = 7474 
    [ 7.500, 10.000) = 1960 
    [10.000, 12.500) = 386 
    [12.500, 15.000) = 279 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.774 ms/op
     p(99.9000) =     14.811 ms/op
     p(99.9900) =     19.815 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.681 ± 3.175  ops/ms
ClientPb.existUser                       thrpt       3  10.334 ± 3.757  ops/ms
ClientPb.getUser                         thrpt       3   9.688 ± 2.677  ops/ms
ClientPb.listUser                        thrpt       3   8.173 ± 4.824  ops/ms
ClientPb.createUser                       avgt       3   3.295 ± 1.481   ms/op
ClientPb.existUser                        avgt       3   3.130 ± 1.726   ms/op
ClientPb.getUser                          avgt       3   3.258 ± 0.513   ms/op
ClientPb.listUser                         avgt       3   3.818 ± 0.503   ms/op
ClientPb.createUser                     sample  289731   3.309 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.296           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.013           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.385           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.509           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.721           ms/op
ClientPb.existUser                      sample  297285   3.227 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.280           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.463           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.779           ms/op
ClientPb.existUser:existUser·p0.9999    sample          37.159           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.436           ms/op
ClientPb.getUser                        sample  292214   3.284 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.245           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.154           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.621           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.586           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.383           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.046           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.183           ms/op
ClientPb.listUser                       sample  250981   3.824 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.906           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.157           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.774           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.811           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.815           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.691           ms/op
