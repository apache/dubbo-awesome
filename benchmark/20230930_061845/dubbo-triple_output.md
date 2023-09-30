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
# Warmup Iteration   1: 1.991 ops/ms
# Warmup Iteration   2: 5.002 ops/ms
# Warmup Iteration   3: 8.325 ops/ms
Iteration   1: 8.838 ops/ms
Iteration   2: 9.218 ops/ms
Iteration   3: 9.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.075 ±(99.9%) 3.770 ops/ms [Average]
  (min, avg, max) = (8.838, 9.075, 9.218), stdev = 0.207
  CI (99.9%): [5.305, 12.844] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.985 ops/ms
# Warmup Iteration   2: 8.515 ops/ms
# Warmup Iteration   3: 9.608 ops/ms
Iteration   1: 9.756 ops/ms
Iteration   2: 9.674 ops/ms
Iteration   3: 9.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.671 ±(99.9%) 1.574 ops/ms [Average]
  (min, avg, max) = (9.584, 9.671, 9.756), stdev = 0.086
  CI (99.9%): [8.097, 11.246] (assumes normal distribution)


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
# Warmup Iteration   1: 2.913 ops/ms
# Warmup Iteration   2: 7.495 ops/ms
# Warmup Iteration   3: 9.103 ops/ms
Iteration   1: 9.162 ops/ms
Iteration   2: 9.118 ops/ms
Iteration   3: 9.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.199 ±(99.9%) 1.900 ops/ms [Average]
  (min, avg, max) = (9.118, 9.199, 9.317), stdev = 0.104
  CI (99.9%): [7.299, 11.099] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.550 ops/ms
# Warmup Iteration   2: 7.132 ops/ms
# Warmup Iteration   3: 7.630 ops/ms
Iteration   1: 7.742 ops/ms
Iteration   2: 7.708 ops/ms
Iteration   3: 7.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.751 ±(99.9%) 0.884 ops/ms [Average]
  (min, avg, max) = (7.708, 7.751, 7.804), stdev = 0.048
  CI (99.9%): [6.867, 8.635] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.969 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.675 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.671 ±(99.9%) 0.007 ms/op
Iteration   1: 3.393 ±(99.9%) 0.007 ms/op
Iteration   2: 3.439 ±(99.9%) 0.003 ms/op
Iteration   3: 3.500 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.444 ±(99.9%) 0.978 ms/op [Average]
  (min, avg, max) = (3.393, 3.444, 3.500), stdev = 0.054
  CI (99.9%): [2.466, 4.421] (assumes normal distribution)


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
# Warmup Iteration   1: 8.519 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.004 ms/op
Iteration   1: 3.397 ±(99.9%) 0.006 ms/op
Iteration   2: 3.362 ±(99.9%) 0.006 ms/op
Iteration   3: 3.360 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.373 ±(99.9%) 0.376 ms/op [Average]
  (min, avg, max) = (3.360, 3.373, 3.397), stdev = 0.021
  CI (99.9%): [2.997, 3.749] (assumes normal distribution)


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
# Warmup Iteration   1: 11.178 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.005 ms/op
Iteration   1: 3.467 ±(99.9%) 0.005 ms/op
Iteration   2: 3.499 ±(99.9%) 0.004 ms/op
Iteration   3: 3.508 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.491 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.467, 3.491, 3.508), stdev = 0.021
  CI (99.9%): [3.104, 3.879] (assumes normal distribution)


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
# Warmup Iteration   1: 11.498 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.631 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.281 ±(99.9%) 0.006 ms/op
Iteration   1: 4.285 ±(99.9%) 0.004 ms/op
Iteration   2: 4.145 ±(99.9%) 0.008 ms/op
Iteration   3: 4.156 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.195 ±(99.9%) 1.417 ms/op [Average]
  (min, avg, max) = (4.145, 4.195, 4.285), stdev = 0.078
  CI (99.9%): [2.778, 5.612] (assumes normal distribution)


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
# Warmup Iteration   1: 10.123 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.514 ±(99.9%) 0.011 ms/op
Iteration   1: 3.828 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.551 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   5.865 ms/op
                 createUser·p0.99:   7.692 ms/op
                 createUser·p0.999:  21.037 ms/op
                 createUser·p0.9999: 31.660 ms/op
                 createUser·p1.00:   33.030 ms/op

Iteration   2: 3.510 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.715 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   3.965 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  15.479 ms/op
                 createUser·p0.9999: 26.706 ms/op
                 createUser·p1.00:   27.329 ms/op

Iteration   3: 3.611 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  21.135 ms/op
                 createUser·p0.9999: 59.712 ms/op
                 createUser·p1.00:   60.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 263438
  mean =      3.645 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 254811 
    [ 5.000, 10.000) = 8005 
    [10.000, 15.000) = 332 
    [15.000, 20.000) = 34 
    [20.000, 25.000) = 102 
    [25.000, 30.000) = 109 
    [30.000, 35.000) = 13 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 18 
    [55.000, 60.000) = 7 
    [60.000, 65.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     19.331 ms/op
     p(99.9900) =     52.275 ms/op
     p(99.9990) =     60.568 ms/op
     p(99.9999) =     60.948 ms/op
    p(100.0000) =     60.948 ms/op


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
# Warmup Iteration   1: 8.648 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.008 ms/op
Iteration   1: 3.388 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   5.767 ms/op
                 existUser·p0.999:  20.859 ms/op
                 existUser·p0.9999: 26.804 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   2: 3.470 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.419 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  13.828 ms/op
                 existUser·p0.9999: 24.634 ms/op
                 existUser·p1.00:   25.264 ms/op

Iteration   3: 3.492 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.372 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  10.493 ms/op
                 existUser·p0.9999: 29.912 ms/op
                 existUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278201
  mean =      3.449 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7997 
    [ 2.500,  5.000) = 262892 
    [ 5.000,  7.500) = 5865 
    [ 7.500, 10.000) = 841 
    [10.000, 12.500) = 306 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 93 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     12.982 ms/op
     p(99.9900) =     28.618 ms/op
     p(99.9990) =     30.561 ms/op
     p(99.9999) =     31.064 ms/op
    p(100.0000) =     31.064 ms/op


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
# Warmup Iteration   1: 9.405 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.010 ms/op
Iteration   1: 3.530 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.491 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   7.356 ms/op
                 getUser·p0.999:  20.493 ms/op
                 getUser·p0.9999: 23.581 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   2: 3.476 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  21.691 ms/op
                 getUser·p0.9999: 24.838 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 3.500 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  18.785 ms/op
                 getUser·p0.9999: 26.144 ms/op
                 getUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273985
  mean =      3.502 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5124 
    [ 2.500,  5.000) = 261165 
    [ 5.000,  7.500) = 6203 
    [ 7.500, 10.000) = 967 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 136 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     27.284 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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
# Warmup Iteration   1: 11.383 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.522 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.248 ±(99.9%) 0.013 ms/op
Iteration   1: 4.216 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  19.732 ms/op
                 listUser·p0.9999: 23.639 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   2: 4.210 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   4.121 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  15.894 ms/op
                 listUser·p0.9999: 17.787 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   3: 4.185 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   4.088 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  15.483 ms/op
                 listUser·p0.9999: 17.772 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228148
  mean =      4.204 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32 
    [ 2.500,  5.000) = 219048 
    [ 5.000,  7.500) = 7196 
    [ 7.500, 10.000) = 1013 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 269 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.683 ms/op
     p(50.0000) =      4.100 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     16.250 ms/op
     p(99.9900) =     23.001 ms/op
     p(99.9990) =     24.232 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.075 ± 3.770  ops/ms
ClientPb.existUser                       thrpt       3   9.671 ± 1.574  ops/ms
ClientPb.getUser                         thrpt       3   9.199 ± 1.900  ops/ms
ClientPb.listUser                        thrpt       3   7.751 ± 0.884  ops/ms
ClientPb.createUser                       avgt       3   3.444 ± 0.978   ms/op
ClientPb.existUser                        avgt       3   3.373 ± 0.376   ms/op
ClientPb.getUser                          avgt       3   3.491 ± 0.388   ms/op
ClientPb.listUser                         avgt       3   4.195 ± 1.417   ms/op
ClientPb.createUser                     sample  263438   3.645 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.715           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.486           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.315           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.331           ms/op
ClientPb.createUser:createUser·p0.9999  sample          52.275           ms/op
ClientPb.createUser:createUser·p1.00    sample          60.948           ms/op
ClientPb.existUser                      sample  278201   3.449 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.977           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.783           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.982           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.618           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.064           ms/op
ClientPb.getUser                        sample  273985   3.502 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.886           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.963           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.792           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.068           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.722           ms/op
ClientPb.listUser                       sample  228148   4.204 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.683           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.143           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.250           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.001           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.609           ms/op
