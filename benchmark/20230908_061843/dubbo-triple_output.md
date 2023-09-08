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
# Warmup Iteration   1: 2.538 ops/ms
# Warmup Iteration   2: 6.430 ops/ms
# Warmup Iteration   3: 9.163 ops/ms
Iteration   1: 9.735 ops/ms
Iteration   2: 9.644 ops/ms
Iteration   3: 9.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.699 ±(99.9%) 0.887 ops/ms [Average]
  (min, avg, max) = (9.644, 9.699, 9.735), stdev = 0.049
  CI (99.9%): [8.813, 10.586] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.499 ops/ms
# Warmup Iteration   2: 9.040 ops/ms
# Warmup Iteration   3: 10.418 ops/ms
Iteration   1: 10.673 ops/ms
Iteration   2: 9.896 ops/ms
Iteration   3: 10.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.250 ±(99.9%) 7.167 ops/ms [Average]
  (min, avg, max) = (9.896, 10.250, 10.673), stdev = 0.393
  CI (99.9%): [3.083, 17.417] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.615 ops/ms
# Warmup Iteration   2: 9.046 ops/ms
# Warmup Iteration   3: 9.625 ops/ms
Iteration   1: 9.776 ops/ms
Iteration   2: 10.202 ops/ms
Iteration   3: 9.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.808 ±(99.9%) 6.906 ops/ms [Average]
  (min, avg, max) = (9.447, 9.808, 10.202), stdev = 0.379
  CI (99.9%): [2.902, 16.715] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.104 ops/ms
# Warmup Iteration   2: 7.715 ops/ms
# Warmup Iteration   3: 8.079 ops/ms
Iteration   1: 8.584 ops/ms
Iteration   2: 8.326 ops/ms
Iteration   3: 8.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.420 ±(99.9%) 2.604 ops/ms [Average]
  (min, avg, max) = (8.326, 8.420, 8.584), stdev = 0.143
  CI (99.9%): [5.816, 11.024] (assumes normal distribution)


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
# Warmup Iteration   1: 7.404 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.006 ms/op
Iteration   1: 3.277 ±(99.9%) 0.004 ms/op
Iteration   2: 3.254 ±(99.9%) 0.007 ms/op
Iteration   3: 3.183 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.238 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (3.183, 3.238, 3.277), stdev = 0.049
  CI (99.9%): [2.341, 4.135] (assumes normal distribution)


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
# Warmup Iteration   1: 6.580 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.352 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.006 ms/op
Iteration   1: 3.216 ±(99.9%) 0.007 ms/op
Iteration   2: 3.191 ±(99.9%) 0.003 ms/op
Iteration   3: 3.102 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.170 ±(99.9%) 1.097 ms/op [Average]
  (min, avg, max) = (3.102, 3.170, 3.216), stdev = 0.060
  CI (99.9%): [2.073, 4.266] (assumes normal distribution)


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
# Warmup Iteration   1: 6.684 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.002 ms/op
Iteration   1: 3.268 ±(99.9%) 0.003 ms/op
Iteration   2: 3.270 ±(99.9%) 0.006 ms/op
Iteration   3: 3.345 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.294 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (3.268, 3.294, 3.345), stdev = 0.044
  CI (99.9%): [2.487, 4.102] (assumes normal distribution)


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
# Warmup Iteration   1: 8.441 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.807 ±(99.9%) 0.006 ms/op
Iteration   1: 3.854 ±(99.9%) 0.004 ms/op
Iteration   2: 3.794 ±(99.9%) 0.004 ms/op
Iteration   3: 3.768 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.806 ±(99.9%) 0.800 ms/op [Average]
  (min, avg, max) = (3.768, 3.806, 3.854), stdev = 0.044
  CI (99.9%): [3.006, 4.605] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.796 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.009 ms/op
Iteration   1: 3.348 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  18.621 ms/op
                 createUser·p0.9999: 21.201 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   2: 3.290 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   6.186 ms/op
                 createUser·p0.999:  16.365 ms/op
                 createUser·p0.9999: 26.003 ms/op
                 createUser·p1.00:   26.739 ms/op

Iteration   3: 3.249 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   5.451 ms/op
                 createUser·p0.999:  16.368 ms/op
                 createUser·p0.9999: 18.453 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291121
  mean =      3.295 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25727 
    [ 2.500,  5.000) = 257948 
    [ 5.000,  7.500) = 6124 
    [ 7.500, 10.000) = 860 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     16.368 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     26.420 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 7.523 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.439 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.007 ms/op
Iteration   1: 3.185 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   6.144 ms/op
                 existUser·p0.999:  14.079 ms/op
                 existUser·p0.9999: 21.004 ms/op
                 existUser·p1.00:   21.922 ms/op

Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.233 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  9.725 ms/op
                 existUser·p0.9999: 19.759 ms/op
                 existUser·p1.00:   20.742 ms/op

Iteration   3: 3.152 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.356 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  12.354 ms/op
                 existUser·p0.9999: 22.408 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304226
  mean =      3.155 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27910 
    [ 2.500,  5.000) = 267789 
    [ 5.000,  7.500) = 7177 
    [ 7.500, 10.000) = 809 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 148 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     20.939 ms/op
     p(99.9990) =     23.100 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 7.649 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.010 ms/op
Iteration   1: 3.226 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.965 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.461 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  16.376 ms/op
                 getUser·p0.9999: 20.582 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.186 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  19.399 ms/op
                 getUser·p0.9999: 22.370 ms/op
                 getUser·p1.00:   23.069 ms/op

Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  9.944 ms/op
                 getUser·p0.9999: 22.086 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299511
  mean =      3.204 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6100 
    [ 2.500,  5.000) = 285131 
    [ 5.000,  7.500) = 6748 
    [ 7.500, 10.000) = 1111 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     17.119 ms/op
     p(99.9900) =     21.956 ms/op
     p(99.9990) =     22.906 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 8.347 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.013 ms/op
Iteration   1: 3.813 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.767 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 24.452 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   2: 3.782 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.635 ms/op
                 listUser·p0.999:  13.631 ms/op
                 listUser·p0.9999: 15.303 ms/op
                 listUser·p1.00:   16.908 ms/op

Iteration   3: 3.750 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.556 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253734
  mean =      3.782 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 244148 
    [ 5.000,  7.500) = 7002 
    [ 7.500, 10.000) = 1777 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 348 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     14.500 ms/op
     p(99.9900) =     21.983 ms/op
     p(99.9990) =     24.851 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.699 ± 0.887  ops/ms
ClientPb.existUser                       thrpt       3  10.250 ± 7.167  ops/ms
ClientPb.getUser                         thrpt       3   9.808 ± 6.906  ops/ms
ClientPb.listUser                        thrpt       3   8.420 ± 2.604  ops/ms
ClientPb.createUser                       avgt       3   3.238 ± 0.897   ms/op
ClientPb.existUser                        avgt       3   3.170 ± 1.097   ms/op
ClientPb.getUser                          avgt       3   3.294 ± 0.807   ms/op
ClientPb.listUser                         avgt       3   3.806 ± 0.800   ms/op
ClientPb.createUser                     sample  291121   3.295 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.137           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.674           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.833           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.368           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.133           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.739           ms/op
ClientPb.existUser                      sample  304226   3.155 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.233           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.923           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.288           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.939           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.986           ms/op
ClientPb.getUser                        sample  299511   3.204 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.965           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.461           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.119           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.956           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.888           ms/op
ClientPb.listUser                       sample  253734   3.782 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.556           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.625           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.447           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.500           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.983           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.166           ms/op
