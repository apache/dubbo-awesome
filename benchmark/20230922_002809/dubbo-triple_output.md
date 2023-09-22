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
# Warmup Iteration   1: 2.323 ops/ms
# Warmup Iteration   2: 6.350 ops/ms
# Warmup Iteration   3: 9.445 ops/ms
Iteration   1: 9.639 ops/ms
Iteration   2: 9.703 ops/ms
Iteration   3: 9.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.772 ±(99.9%) 3.247 ops/ms [Average]
  (min, avg, max) = (9.639, 9.772, 9.974), stdev = 0.178
  CI (99.9%): [6.525, 13.019] (assumes normal distribution)


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
# Warmup Iteration   1: 3.802 ops/ms
# Warmup Iteration   2: 9.580 ops/ms
# Warmup Iteration   3: 10.061 ops/ms
Iteration   1: 10.349 ops/ms
Iteration   2: 10.036 ops/ms
Iteration   3: 10.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.185 ±(99.9%) 2.866 ops/ms [Average]
  (min, avg, max) = (10.036, 10.185, 10.349), stdev = 0.157
  CI (99.9%): [7.319, 13.050] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.743 ops/ms
# Warmup Iteration   2: 9.436 ops/ms
# Warmup Iteration   3: 9.612 ops/ms
Iteration   1: 9.774 ops/ms
Iteration   2: 9.831 ops/ms
Iteration   3: 9.712 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.772 ±(99.9%) 1.091 ops/ms [Average]
  (min, avg, max) = (9.712, 9.772, 9.831), stdev = 0.060
  CI (99.9%): [8.681, 10.863] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.157 ops/ms
# Warmup Iteration   2: 7.953 ops/ms
# Warmup Iteration   3: 8.287 ops/ms
Iteration   1: 8.397 ops/ms
Iteration   2: 8.546 ops/ms
Iteration   3: 8.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.473 ±(99.9%) 1.364 ops/ms [Average]
  (min, avg, max) = (8.397, 8.473, 8.546), stdev = 0.075
  CI (99.9%): [7.109, 9.837] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.718 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.347 ±(99.9%) 0.003 ms/op
Iteration   1: 3.239 ±(99.9%) 0.003 ms/op
Iteration   2: 3.321 ±(99.9%) 0.003 ms/op
Iteration   3: 3.218 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.259 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (3.218, 3.259, 3.321), stdev = 0.054
  CI (99.9%): [2.267, 4.251] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.698 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.383 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.003 ms/op
Iteration   1: 3.140 ±(99.9%) 0.006 ms/op
Iteration   2: 3.103 ±(99.9%) 0.002 ms/op
Iteration   3: 3.133 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.125 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (3.103, 3.125, 3.140), stdev = 0.020
  CI (99.9%): [2.767, 3.484] (assumes normal distribution)


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
# Warmup Iteration   1: 7.170 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.400 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.002 ms/op
Iteration   1: 3.269 ±(99.9%) 0.002 ms/op
Iteration   2: 3.222 ±(99.9%) 0.003 ms/op
Iteration   3: 3.286 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.259 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (3.222, 3.259, 3.286), stdev = 0.033
  CI (99.9%): [2.658, 3.861] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.606 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.005 ms/op
Iteration   1: 3.771 ±(99.9%) 0.004 ms/op
Iteration   2: 3.756 ±(99.9%) 0.006 ms/op
Iteration   3: 3.792 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.773 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.756, 3.773, 3.792), stdev = 0.018
  CI (99.9%): [3.446, 4.101] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.135 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.008 ms/op
Iteration   1: 3.290 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  16.823 ms/op
                 createUser·p0.9999: 21.350 ms/op
                 createUser·p1.00:   22.348 ms/op

Iteration   2: 3.340 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.184 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 21.725 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   3: 3.324 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.798 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.202 ms/op
                 createUser·p0.999:  16.141 ms/op
                 createUser·p0.9999: 24.347 ms/op
                 createUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289326
  mean =      3.318 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15533 
    [ 2.500,  5.000) = 269544 
    [ 5.000,  7.500) = 3146 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     23.986 ms/op
     p(99.9990) =     25.537 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.495 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.211 ±(99.9%) 0.007 ms/op
Iteration   1: 3.208 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.183 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  12.018 ms/op
                 existUser·p0.9999: 16.270 ms/op
                 existUser·p1.00:   16.908 ms/op

Iteration   2: 3.206 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.436 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.390 ms/op
                 existUser·p0.999:  15.082 ms/op
                 existUser·p0.9999: 17.793 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   3: 3.305 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.116 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.660 ms/op
                 existUser·p0.999:  14.974 ms/op
                 existUser·p0.9999: 20.742 ms/op
                 existUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296408
  mean =      3.239 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12306 
    [ 2.500,  5.000) = 277431 
    [ 5.000,  7.500) = 5744 
    [ 7.500, 10.000) = 477 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     14.781 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     21.300 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 9.697 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.009 ms/op
Iteration   1: 3.408 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  17.600 ms/op
                 getUser·p0.9999: 22.826 ms/op
                 getUser·p1.00:   23.986 ms/op

Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   5.317 ms/op
                 getUser·p0.999:  11.499 ms/op
                 getUser·p0.9999: 25.526 ms/op
                 getUser·p1.00:   26.018 ms/op

Iteration   3: 3.258 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.311 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  14.448 ms/op
                 getUser·p0.9999: 20.000 ms/op
                 getUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 292347
  mean =      3.284 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13393 
    [ 2.500,  5.000) = 271401 
    [ 5.000,  7.500) = 6309 
    [ 7.500, 10.000) = 675 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      6.611 ms/op
     p(99.9000) =     15.461 ms/op
     p(99.9900) =     24.601 ms/op
     p(99.9990) =     25.826 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 9.915 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.009 ms/op
Iteration   1: 3.799 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.436 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  16.145 ms/op
                 listUser·p0.9999: 20.889 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   2: 3.892 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  14.645 ms/op
                 listUser·p0.9999: 15.529 ms/op
                 listUser·p1.00:   16.302 ms/op

Iteration   3: 3.803 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.941 ms/op
                 listUser·p0.9999: 15.788 ms/op
                 listUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250385
  mean =      3.831 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 243766 
    [ 5.000,  7.500) = 5051 
    [ 7.500, 10.000) = 606 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 412 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     18.611 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.772 ± 3.247  ops/ms
ClientPb.existUser                       thrpt       3  10.185 ± 2.866  ops/ms
ClientPb.getUser                         thrpt       3   9.772 ± 1.091  ops/ms
ClientPb.listUser                        thrpt       3   8.473 ± 1.364  ops/ms
ClientPb.createUser                       avgt       3   3.259 ± 0.992   ms/op
ClientPb.existUser                        avgt       3   3.125 ± 0.359   ms/op
ClientPb.getUser                          avgt       3   3.259 ± 0.602   ms/op
ClientPb.listUser                         avgt       3   3.773 ± 0.328   ms/op
ClientPb.createUser                     sample  289326   3.318 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.798           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.974           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.986           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.080           ms/op
ClientPb.existUser                      sample  296408   3.239 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.116           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.078           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.781           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.087           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.529           ms/op
ClientPb.getUser                        sample  292347   3.284 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.037           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.611           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.461           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.601           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.018           ms/op
ClientPb.listUser                       sample  250385   3.831 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.436           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.190           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.816           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.680           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.611           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.379           ms/op
