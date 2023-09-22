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
# Warmup Iteration   1: 2.346 ops/ms
# Warmup Iteration   2: 6.057 ops/ms
# Warmup Iteration   3: 8.385 ops/ms
Iteration   1: 9.271 ops/ms
Iteration   2: 9.184 ops/ms
Iteration   3: 9.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.253 ±(99.9%) 1.121 ops/ms [Average]
  (min, avg, max) = (9.184, 9.253, 9.303), stdev = 0.061
  CI (99.9%): [8.132, 10.374] (assumes normal distribution)


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
# Warmup Iteration   1: 3.587 ops/ms
# Warmup Iteration   2: 8.938 ops/ms
# Warmup Iteration   3: 9.542 ops/ms
Iteration   1: 9.865 ops/ms
Iteration   2: 9.898 ops/ms
Iteration   3: 9.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.761 ±(99.9%) 3.825 ops/ms [Average]
  (min, avg, max) = (9.520, 9.761, 9.898), stdev = 0.210
  CI (99.9%): [5.936, 13.586] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.907 ops/ms
# Warmup Iteration   2: 8.322 ops/ms
# Warmup Iteration   3: 9.230 ops/ms
Iteration   1: 9.219 ops/ms
Iteration   2: 9.173 ops/ms
Iteration   3: 9.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.212 ±(99.9%) 0.638 ops/ms [Average]
  (min, avg, max) = (9.173, 9.212, 9.242), stdev = 0.035
  CI (99.9%): [8.574, 9.849] (assumes normal distribution)


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
# Warmup Iteration   1: 2.819 ops/ms
# Warmup Iteration   2: 7.217 ops/ms
# Warmup Iteration   3: 7.561 ops/ms
Iteration   1: 7.710 ops/ms
Iteration   2: 8.036 ops/ms
Iteration   3: 7.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.832 ±(99.9%) 3.242 ops/ms [Average]
  (min, avg, max) = (7.710, 7.832, 8.036), stdev = 0.178
  CI (99.9%): [4.590, 11.074] (assumes normal distribution)


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
# Warmup Iteration   1: 10.124 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.004 ms/op
Iteration   1: 3.418 ±(99.9%) 0.004 ms/op
Iteration   2: 3.429 ±(99.9%) 0.005 ms/op
Iteration   3: 3.422 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.423 ±(99.9%) 0.108 ms/op [Average]
  (min, avg, max) = (3.418, 3.423, 3.429), stdev = 0.006
  CI (99.9%): [3.315, 3.531] (assumes normal distribution)


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
# Warmup Iteration   1: 7.443 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.004 ms/op
Iteration   1: 3.256 ±(99.9%) 0.004 ms/op
Iteration   2: 3.354 ±(99.9%) 0.005 ms/op
Iteration   3: 3.310 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.307 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (3.256, 3.307, 3.354), stdev = 0.049
  CI (99.9%): [2.410, 4.203] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.546 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.452 ±(99.9%) 0.004 ms/op
Iteration   1: 3.500 ±(99.9%) 0.003 ms/op
Iteration   2: 3.387 ±(99.9%) 0.005 ms/op
Iteration   3: 3.380 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.422 ±(99.9%) 1.223 ms/op [Average]
  (min, avg, max) = (3.380, 3.422, 3.500), stdev = 0.067
  CI (99.9%): [2.199, 4.645] (assumes normal distribution)


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
# Warmup Iteration   1: 8.508 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.322 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.061 ±(99.9%) 0.006 ms/op
Iteration   1: 4.039 ±(99.9%) 0.009 ms/op
Iteration   2: 4.067 ±(99.9%) 0.006 ms/op
Iteration   3: 3.991 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.033 ±(99.9%) 0.703 ms/op [Average]
  (min, avg, max) = (3.991, 4.033, 4.067), stdev = 0.039
  CI (99.9%): [3.330, 4.735] (assumes normal distribution)


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
# Warmup Iteration   1: 8.551 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.011 ms/op
Iteration   1: 3.489 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  18.219 ms/op
                 createUser·p0.9999: 35.313 ms/op
                 createUser·p1.00:   38.928 ms/op

Iteration   2: 3.489 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   7.048 ms/op
                 createUser·p0.999:  20.229 ms/op
                 createUser·p0.9999: 21.938 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   3: 3.506 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.577 ms/op
                 createUser·p0.999:  19.542 ms/op
                 createUser·p0.9999: 26.169 ms/op
                 createUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274584
  mean =      3.495 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5638 
    [ 2.500,  5.000) = 259689 
    [ 5.000,  7.500) = 7499 
    [ 7.500, 10.000) = 993 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     19.445 ms/op
     p(99.9900) =     33.803 ms/op
     p(99.9990) =     38.372 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


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
# Warmup Iteration   1: 8.465 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.010 ms/op
Iteration   1: 3.311 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.940 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   6.815 ms/op
                 existUser·p0.999:  11.836 ms/op
                 existUser·p0.9999: 21.146 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   2: 3.404 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.264 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  21.239 ms/op
                 existUser·p0.9999: 24.793 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   3: 3.375 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.071 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.180 ms/op
                 existUser·p0.99:   6.906 ms/op
                 existUser·p0.999:  19.380 ms/op
                 existUser·p0.9999: 26.247 ms/op
                 existUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285309
  mean =      3.363 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6895 
    [ 2.500,  5.000) = 269270 
    [ 5.000,  7.500) = 7449 
    [ 7.500, 10.000) = 1003 
    [10.000, 12.500) = 331 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     14.577 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     26.542 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 9.538 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.689 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.013 ms/op
Iteration   1: 3.510 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.726 ms/op
                 getUser·p0.999:  19.595 ms/op
                 getUser·p0.9999: 25.625 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   2: 3.446 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.121 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  16.697 ms/op
                 getUser·p0.9999: 25.100 ms/op
                 getUser·p1.00:   26.116 ms/op

Iteration   3: 3.452 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  17.774 ms/op
                 getUser·p0.9999: 26.517 ms/op
                 getUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276711
  mean =      3.469 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7950 
    [ 2.500,  5.000) = 259397 
    [ 5.000,  7.500) = 7768 
    [ 7.500, 10.000) = 848 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      0.914 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     25.701 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 10.768 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.015 ms/op
Iteration   1: 4.128 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  19.825 ms/op
                 listUser·p0.9999: 24.772 ms/op
                 listUser·p1.00:   25.362 ms/op

Iteration   2: 4.088 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   8.021 ms/op
                 listUser·p0.999:  17.382 ms/op
                 listUser·p0.9999: 27.760 ms/op
                 listUser·p1.00:   28.672 ms/op

Iteration   3: 4.172 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  16.692 ms/op
                 listUser·p0.9999: 31.588 ms/op
                 listUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232403
  mean =      4.129 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 222063 
    [ 5.000,  7.500) = 7718 
    [ 7.500, 10.000) = 1626 
    [10.000, 12.500) = 215 
    [12.500, 15.000) = 345 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     18.343 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     33.424 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.253 ± 1.121  ops/ms
ClientPb.existUser                       thrpt       3   9.761 ± 3.825  ops/ms
ClientPb.getUser                         thrpt       3   9.212 ± 0.638  ops/ms
ClientPb.listUser                        thrpt       3   7.832 ± 3.242  ops/ms
ClientPb.createUser                       avgt       3   3.423 ± 0.108   ms/op
ClientPb.existUser                        avgt       3   3.307 ± 0.897   ms/op
ClientPb.getUser                          avgt       3   3.422 ± 1.223   ms/op
ClientPb.listUser                         avgt       3   4.033 ± 0.703   ms/op
ClientPb.createUser                     sample  274584   3.495 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.886           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.318           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.006           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.947           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.445           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.803           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.928           ms/op
ClientPb.existUser                      sample  285309   3.363 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.940           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.577           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.723           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.640           ms/op
ClientPb.getUser                        sample  276711   3.469 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.914           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.914           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.760           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.701           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.558           ms/op
ClientPb.listUser                       sample  232403   4.129 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.262           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.949           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.899           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.635           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.343           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.212           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.472           ms/op
