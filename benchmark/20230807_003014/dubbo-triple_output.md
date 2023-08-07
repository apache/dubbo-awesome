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
# Warmup Iteration   1: 2.024 ops/ms
# Warmup Iteration   2: 4.655 ops/ms
# Warmup Iteration   3: 8.403 ops/ms
Iteration   1: 8.816 ops/ms
Iteration   2: 9.018 ops/ms
Iteration   3: 8.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.876 ±(99.9%) 2.251 ops/ms [Average]
  (min, avg, max) = (8.794, 8.876, 9.018), stdev = 0.123
  CI (99.9%): [6.625, 11.127] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.544 ops/ms
# Warmup Iteration   2: 8.226 ops/ms
# Warmup Iteration   3: 9.105 ops/ms
Iteration   1: 9.362 ops/ms
Iteration   2: 9.237 ops/ms
Iteration   3: 9.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.420 ±(99.9%) 3.953 ops/ms [Average]
  (min, avg, max) = (9.237, 9.420, 9.659), stdev = 0.217
  CI (99.9%): [5.467, 13.372] (assumes normal distribution)


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
# Warmup Iteration   1: 2.647 ops/ms
# Warmup Iteration   2: 8.031 ops/ms
# Warmup Iteration   3: 8.918 ops/ms
Iteration   1: 8.940 ops/ms
Iteration   2: 9.047 ops/ms
Iteration   3: 8.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.924 ±(99.9%) 2.402 ops/ms [Average]
  (min, avg, max) = (8.785, 8.924, 9.047), stdev = 0.132
  CI (99.9%): [6.522, 11.326] (assumes normal distribution)


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
# Warmup Iteration   1: 2.665 ops/ms
# Warmup Iteration   2: 6.830 ops/ms
# Warmup Iteration   3: 7.473 ops/ms
Iteration   1: 7.567 ops/ms
Iteration   2: 7.737 ops/ms
Iteration   3: 7.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.585 ±(99.9%) 2.625 ops/ms [Average]
  (min, avg, max) = (7.451, 7.585, 7.737), stdev = 0.144
  CI (99.9%): [4.960, 10.210] (assumes normal distribution)


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
# Warmup Iteration   1: 11.772 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.006 ms/op
Iteration   1: 3.695 ±(99.9%) 0.005 ms/op
Iteration   2: 3.666 ±(99.9%) 0.003 ms/op
Iteration   3: 3.478 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.613 ±(99.9%) 2.148 ms/op [Average]
  (min, avg, max) = (3.478, 3.613, 3.695), stdev = 0.118
  CI (99.9%): [1.465, 5.761] (assumes normal distribution)


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
# Warmup Iteration   1: 8.986 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.004 ms/op
Iteration   1: 3.331 ±(99.9%) 0.007 ms/op
Iteration   2: 3.387 ±(99.9%) 0.006 ms/op
Iteration   3: 3.267 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.329 ±(99.9%) 1.098 ms/op [Average]
  (min, avg, max) = (3.267, 3.329, 3.387), stdev = 0.060
  CI (99.9%): [2.231, 4.426] (assumes normal distribution)


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
# Warmup Iteration   1: 11.112 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.005 ms/op
Iteration   1: 3.577 ±(99.9%) 0.006 ms/op
Iteration   2: 3.529 ±(99.9%) 0.004 ms/op
Iteration   3: 3.410 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.505 ±(99.9%) 1.572 ms/op [Average]
  (min, avg, max) = (3.410, 3.505, 3.577), stdev = 0.086
  CI (99.9%): [1.934, 5.077] (assumes normal distribution)


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
# Warmup Iteration   1: 11.794 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.177 ±(99.9%) 0.006 ms/op
Iteration   1: 4.079 ±(99.9%) 0.008 ms/op
Iteration   2: 4.080 ±(99.9%) 0.009 ms/op
Iteration   3: 3.970 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.043 ±(99.9%) 1.152 ms/op [Average]
  (min, avg, max) = (3.970, 4.043, 4.080), stdev = 0.063
  CI (99.9%): [2.890, 5.195] (assumes normal distribution)


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
# Warmup Iteration   1: 10.296 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.629 ±(99.9%) 0.011 ms/op
Iteration   1: 3.863 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   6.652 ms/op
                 createUser·p0.99:   7.895 ms/op
                 createUser·p0.999:  21.141 ms/op
                 createUser·p0.9999: 24.426 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   2: 3.472 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   6.469 ms/op
                 createUser·p0.999:  23.200 ms/op
                 createUser·p0.9999: 25.749 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   3: 3.534 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.573 ms/op
                 createUser·p0.50:   3.420 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  25.100 ms/op
                 createUser·p0.9999: 30.306 ms/op
                 createUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 265572
  mean =      3.615 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4365 
    [ 2.500,  5.000) = 248544 
    [ 5.000,  7.500) = 9883 
    [ 7.500, 10.000) = 2166 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 121 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.537 ms/op
     p(99.9000) =     21.987 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     32.834 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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
# Warmup Iteration   1: 10.122 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 3.623 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.010 ms/op
Iteration   1: 3.316 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.694 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   6.238 ms/op
                 existUser·p0.999:  15.254 ms/op
                 existUser·p0.9999: 23.072 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   2: 3.353 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.628 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  21.706 ms/op
                 existUser·p0.9999: 24.442 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   3: 3.431 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   6.980 ms/op
                 existUser·p0.999:  19.625 ms/op
                 existUser·p0.9999: 30.414 ms/op
                 existUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284870
  mean =      3.366 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8972 
    [ 2.500,  5.000) = 269030 
    [ 5.000,  7.500) = 5343 
    [ 7.500, 10.000) = 982 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     29.688 ms/op
     p(99.9990) =     30.807 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 9.280 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.704 ±(99.9%) 0.016 ms/op
Iteration   1: 3.526 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   4.043 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  21.085 ms/op
                 getUser·p0.9999: 23.757 ms/op
                 getUser·p1.00:   24.314 ms/op

Iteration   2: 3.467 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.573 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   6.277 ms/op
                 getUser·p0.999:  24.072 ms/op
                 getUser·p0.9999: 27.953 ms/op
                 getUser·p1.00:   28.377 ms/op

Iteration   3: 3.645 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.626 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  19.867 ms/op
                 getUser·p0.9999: 28.425 ms/op
                 getUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270856
  mean =      3.544 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5774 
    [ 2.500,  5.000) = 253548 
    [ 5.000,  7.500) = 9782 
    [ 7.500, 10.000) = 1244 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 104 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      1.018 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     20.354 ms/op
     p(99.9900) =     27.847 ms/op
     p(99.9990) =     28.803 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 11.821 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 4.631 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.015 ms/op
Iteration   1: 4.177 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   4.022 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   8.233 ms/op
                 listUser·p0.999:  23.822 ms/op
                 listUser·p0.9999: 26.324 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 4.256 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  15.745 ms/op
                 listUser·p0.9999: 19.382 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   3: 4.171 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.220 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  13.852 ms/op
                 listUser·p0.9999: 15.958 ms/op
                 listUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228295
  mean =      4.201 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 214645 
    [ 5.000,  7.500) = 9902 
    [ 7.500, 10.000) = 2608 
    [10.000, 12.500) = 616 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.438 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      4.678 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     15.925 ms/op
     p(99.9900) =     25.707 ms/op
     p(99.9990) =     26.645 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.876 ± 2.251  ops/ms
ClientPb.existUser                       thrpt       3   9.420 ± 3.953  ops/ms
ClientPb.getUser                         thrpt       3   8.924 ± 2.402  ops/ms
ClientPb.listUser                        thrpt       3   7.585 ± 2.625  ops/ms
ClientPb.createUser                       avgt       3   3.613 ± 2.148   ms/op
ClientPb.existUser                        avgt       3   3.329 ± 1.098   ms/op
ClientPb.getUser                          avgt       3   3.505 ± 1.572   ms/op
ClientPb.listUser                         avgt       3   4.043 ± 1.152   ms/op
ClientPb.createUser                     sample  265572   3.615 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.192           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.428           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.121           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.833           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.537           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.987           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.212           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.834           ms/op
ClientPb.existUser                      sample  284870   3.366 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.067           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.463           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.744           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.688           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.900           ms/op
ClientPb.getUser                        sample  270856   3.544 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.018           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.355           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.669           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.889           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.354           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.847           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.065           ms/op
ClientPb.listUser                       sample  228295   4.201 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.438           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.678           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.194           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.925           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.707           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
