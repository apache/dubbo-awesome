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
# Warmup Iteration   1: 2.472 ops/ms
# Warmup Iteration   2: 6.487 ops/ms
# Warmup Iteration   3: 9.446 ops/ms
Iteration   1: 9.290 ops/ms
Iteration   2: 10.019 ops/ms
Iteration   3: 9.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.691 ±(99.9%) 6.752 ops/ms [Average]
  (min, avg, max) = (9.290, 9.691, 10.019), stdev = 0.370
  CI (99.9%): [2.938, 16.443] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.690 ops/ms
# Warmup Iteration   2: 9.605 ops/ms
# Warmup Iteration   3: 10.066 ops/ms
Iteration   1: 10.419 ops/ms
Iteration   2: 10.453 ops/ms
Iteration   3: 10.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.498 ±(99.9%) 1.978 ops/ms [Average]
  (min, avg, max) = (10.419, 10.498, 10.621), stdev = 0.108
  CI (99.9%): [8.520, 12.475] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.894 ops/ms
# Warmup Iteration   2: 9.013 ops/ms
# Warmup Iteration   3: 9.799 ops/ms
Iteration   1: 9.988 ops/ms
Iteration   2: 10.269 ops/ms
Iteration   3: 10.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.107 ±(99.9%) 2.660 ops/ms [Average]
  (min, avg, max) = (9.988, 10.107, 10.269), stdev = 0.146
  CI (99.9%): [7.446, 12.767] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.815 ops/ms
# Warmup Iteration   2: 8.005 ops/ms
# Warmup Iteration   3: 8.278 ops/ms
Iteration   1: 8.449 ops/ms
Iteration   2: 8.665 ops/ms
Iteration   3: 8.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.504 ±(99.9%) 2.590 ops/ms [Average]
  (min, avg, max) = (8.398, 8.504, 8.665), stdev = 0.142
  CI (99.9%): [5.914, 11.094] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.732 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.319 ±(99.9%) 0.005 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
Iteration   2: 3.187 ±(99.9%) 0.007 ms/op
Iteration   3: 3.066 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.129 ±(99.9%) 1.107 ms/op [Average]
  (min, avg, max) = (3.066, 3.129, 3.187), stdev = 0.061
  CI (99.9%): [2.022, 4.235] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.978 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.003 ms/op
Iteration   1: 3.106 ±(99.9%) 0.008 ms/op
Iteration   2: 3.121 ±(99.9%) 0.008 ms/op
Iteration   3: 3.063 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.097 ±(99.9%) 0.555 ms/op [Average]
  (min, avg, max) = (3.063, 3.097, 3.121), stdev = 0.030
  CI (99.9%): [2.541, 3.652] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.353 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.002 ms/op
Iteration   1: 3.203 ±(99.9%) 0.003 ms/op
Iteration   2: 3.325 ±(99.9%) 0.003 ms/op
Iteration   3: 3.102 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.210 ±(99.9%) 2.032 ms/op [Average]
  (min, avg, max) = (3.102, 3.210, 3.325), stdev = 0.111
  CI (99.9%): [1.178, 5.242] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.151 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.221 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.776 ±(99.9%) 0.008 ms/op
Iteration   1: 3.725 ±(99.9%) 0.009 ms/op
Iteration   2: 3.667 ±(99.9%) 0.006 ms/op
Iteration   3: 3.761 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.717 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (3.667, 3.717, 3.761), stdev = 0.047
  CI (99.9%): [2.855, 4.580] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.676 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.247 ±(99.9%) 0.008 ms/op
Iteration   1: 3.280 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.906 ms/op
                 createUser·p0.999:  10.765 ms/op
                 createUser·p0.9999: 19.956 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   2: 3.230 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.016 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.663 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  19.366 ms/op
                 createUser·p0.9999: 21.449 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   3: 3.153 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.991 ms/op
                 createUser·p0.999:  14.579 ms/op
                 createUser·p0.9999: 23.003 ms/op
                 createUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298029
  mean =      3.220 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20725 
    [ 2.500,  5.000) = 270128 
    [ 5.000,  7.500) = 6335 
    [ 7.500, 10.000) = 361 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 168 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     17.006 ms/op
     p(99.9900) =     22.052 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 6.578 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.430 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.008 ms/op
Iteration   1: 2.996 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.121 ms/op
                 existUser·p0.95:   3.195 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  8.835 ms/op
                 existUser·p0.9999: 19.137 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  8.094 ms/op
                 existUser·p0.9999: 21.427 ms/op
                 existUser·p1.00:   21.823 ms/op

Iteration   3: 3.105 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.608 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  8.339 ms/op
                 existUser·p0.9999: 21.639 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 310781
  mean =      3.088 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23349 
    [ 2.500,  5.000) = 283291 
    [ 5.000,  7.500) = 3649 
    [ 7.500, 10.000) = 204 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 145 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =      8.353 ms/op
     p(99.9900) =     21.329 ms/op
     p(99.9990) =     21.918 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 7.071 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.244 ±(99.9%) 0.010 ms/op
Iteration   1: 3.162 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.044 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  18.638 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.578 ms/op

Iteration   2: 3.187 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.337 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 22.477 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   3: 3.291 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.147 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  8.501 ms/op
                 getUser·p0.9999: 20.382 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298829
  mean =      3.213 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19959 
    [ 2.500,  5.000) = 272651 
    [ 5.000,  7.500) = 5436 
    [ 7.500, 10.000) = 474 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 156 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     10.393 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     23.301 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 9.547 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.013 ms/op
Iteration   1: 3.650 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.572 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.063 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  15.745 ms/op
                 listUser·p0.9999: 21.778 ms/op
                 listUser·p1.00:   22.446 ms/op

Iteration   2: 3.733 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.088 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   3: 3.697 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  12.616 ms/op
                 listUser·p0.9999: 14.467 ms/op
                 listUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259716
  mean =      3.693 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 252709 
    [ 5.000,  7.500) = 5423 
    [ 7.500, 10.000) = 838 
    [10.000, 12.500) = 264 
    [12.500, 15.000) = 224 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     21.169 ms/op
     p(99.9990) =     22.721 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.691 ± 6.752  ops/ms
ClientPb.existUser                       thrpt       3  10.498 ± 1.978  ops/ms
ClientPb.getUser                         thrpt       3  10.107 ± 2.660  ops/ms
ClientPb.listUser                        thrpt       3   8.504 ± 2.590  ops/ms
ClientPb.createUser                       avgt       3   3.129 ± 1.107   ms/op
ClientPb.existUser                        avgt       3   3.097 ± 0.555   ms/op
ClientPb.getUser                          avgt       3   3.210 ± 2.032   ms/op
ClientPb.listUser                         avgt       3   3.717 ± 0.863   ms/op
ClientPb.createUser                     sample  298029   3.220 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.775           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.158           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.571           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.006           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.052           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.396           ms/op
ClientPb.existUser                      sample  310781   3.088 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.029           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.353           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.329           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.151           ms/op
ClientPb.getUser                        sample  298829   3.213 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.044           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.633           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          10.393           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.758           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.052           ms/op
ClientPb.listUser                       sample  259716   3.693 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.247           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.002           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.636           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.107           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.169           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.741           ms/op
