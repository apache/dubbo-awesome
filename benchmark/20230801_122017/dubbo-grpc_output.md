# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.241 ops/ms
# Warmup Iteration   2: 4.766 ops/ms
# Warmup Iteration   3: 6.674 ops/ms
Iteration   1: 6.938 ops/ms
Iteration   2: 7.104 ops/ms
Iteration   3: 7.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.086 ±(99.9%) 2.539 ops/ms [Average]
  (min, avg, max) = (6.938, 7.086, 7.215), stdev = 0.139
  CI (99.9%): [4.547, 9.625] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.346 ops/ms
# Warmup Iteration   2: 6.991 ops/ms
# Warmup Iteration   3: 7.708 ops/ms
Iteration   1: 7.885 ops/ms
Iteration   2: 7.662 ops/ms
Iteration   3: 7.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.764 ±(99.9%) 2.059 ops/ms [Average]
  (min, avg, max) = (7.662, 7.764, 7.885), stdev = 0.113
  CI (99.9%): [5.705, 9.822] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.072 ops/ms
# Warmup Iteration   2: 6.660 ops/ms
# Warmup Iteration   3: 7.049 ops/ms
Iteration   1: 7.024 ops/ms
Iteration   2: 7.182 ops/ms
Iteration   3: 7.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.181 ±(99.9%) 2.859 ops/ms [Average]
  (min, avg, max) = (7.024, 7.181, 7.338), stdev = 0.157
  CI (99.9%): [4.322, 10.040] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.466 ops/ms
# Warmup Iteration   2: 5.059 ops/ms
# Warmup Iteration   3: 5.514 ops/ms
Iteration   1: 5.410 ops/ms
Iteration   2: 5.353 ops/ms
Iteration   3: 5.540 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.434 ±(99.9%) 1.747 ops/ms [Average]
  (min, avg, max) = (5.353, 5.434, 5.540), stdev = 0.096
  CI (99.9%): [3.687, 7.181] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.764 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.581 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.573 ±(99.9%) 0.013 ms/op
Iteration   1: 4.465 ±(99.9%) 0.004 ms/op
Iteration   2: 4.423 ±(99.9%) 0.005 ms/op
Iteration   3: 4.446 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.445 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (4.423, 4.445, 4.465), stdev = 0.021
  CI (99.9%): [4.065, 4.824] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.919 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.004 ms/op
Iteration   1: 4.234 ±(99.9%) 0.004 ms/op
Iteration   2: 4.232 ±(99.9%) 0.003 ms/op
Iteration   3: 4.155 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.207 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (4.155, 4.207, 4.234), stdev = 0.045
  CI (99.9%): [3.381, 5.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.972 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 5.081 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.681 ±(99.9%) 0.008 ms/op
Iteration   1: 4.588 ±(99.9%) 0.005 ms/op
Iteration   2: 4.441 ±(99.9%) 0.004 ms/op
Iteration   3: 4.443 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.491 ±(99.9%) 1.537 ms/op [Average]
  (min, avg, max) = (4.441, 4.491, 4.588), stdev = 0.084
  CI (99.9%): [2.954, 6.027] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.670 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 6.323 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.823 ±(99.9%) 0.027 ms/op
Iteration   1: 5.790 ±(99.9%) 0.016 ms/op
Iteration   2: 5.500 ±(99.9%) 0.011 ms/op
Iteration   3: 5.709 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.666 ±(99.9%) 2.736 ms/op [Average]
  (min, avg, max) = (5.500, 5.666, 5.790), stdev = 0.150
  CI (99.9%): [2.931, 8.402] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.815 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.953 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.508 ±(99.9%) 0.014 ms/op
Iteration   1: 4.426 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.603 ms/op
                 createUser·p0.95:   6.242 ms/op
                 createUser·p0.99:   8.569 ms/op
                 createUser·p0.999:  13.201 ms/op
                 createUser·p0.9999: 15.745 ms/op
                 createUser·p1.00:   16.335 ms/op

Iteration   2: 4.395 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   4.260 ms/op
                 createUser·p0.90:   5.554 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   7.635 ms/op
                 createUser·p0.999:  14.305 ms/op
                 createUser·p0.9999: 19.750 ms/op
                 createUser·p1.00:   19.923 ms/op

Iteration   3: 4.170 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.135 ms/op
                 createUser·p0.50:   4.071 ms/op
                 createUser·p0.90:   5.259 ms/op
                 createUser·p0.95:   5.726 ms/op
                 createUser·p0.99:   7.070 ms/op
                 createUser·p0.999:  11.982 ms/op
                 createUser·p0.9999: 23.342 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 221852
  mean =      4.327 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5653 
    [ 2.500,  5.000) = 174207 
    [ 5.000,  7.500) = 39160 
    [ 7.500, 10.000) = 2299 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.472 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.885 ms/op
     p(99.9000) =     13.044 ms/op
     p(99.9900) =     22.047 ms/op
     p(99.9990) =     23.677 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.022 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.312 ±(99.9%) 0.012 ms/op
Iteration   1: 4.234 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.360 ms/op
                 existUser·p0.50:   4.149 ms/op
                 existUser·p0.90:   5.292 ms/op
                 existUser·p0.95:   5.775 ms/op
                 existUser·p0.99:   7.516 ms/op
                 existUser·p0.999:  12.255 ms/op
                 existUser·p0.9999: 18.692 ms/op
                 existUser·p1.00:   19.694 ms/op

Iteration   2: 4.143 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   4.039 ms/op
                 existUser·p0.90:   5.071 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   6.899 ms/op
                 existUser·p0.999:  11.156 ms/op
                 existUser·p0.9999: 34.341 ms/op
                 existUser·p1.00:   34.669 ms/op

Iteration   3: 4.128 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.990 ms/op
                 existUser·p0.90:   5.153 ms/op
                 existUser·p0.95:   5.677 ms/op
                 existUser·p0.99:   7.979 ms/op
                 existUser·p0.999:  14.010 ms/op
                 existUser·p0.9999: 19.694 ms/op
                 existUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 230191
  mean =      4.168 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7121 
    [ 2.500,  5.000) = 192774 
    [ 5.000,  7.500) = 28011 
    [ 7.500, 10.000) = 1752 
    [10.000, 12.500) = 291 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.360 ms/op
     p(50.0000) =      4.055 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     12.780 ms/op
     p(99.9900) =     33.156 ms/op
     p(99.9990) =     34.603 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.606 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.566 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.406 ±(99.9%) 0.013 ms/op
Iteration   1: 4.220 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.693 ms/op
                 getUser·p0.50:   4.092 ms/op
                 getUser·p0.90:   5.300 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   7.733 ms/op
                 getUser·p0.999:  12.380 ms/op
                 getUser·p0.9999: 22.506 ms/op
                 getUser·p1.00:   22.872 ms/op

Iteration   2: 4.438 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   4.301 ms/op
                 getUser·p0.90:   5.571 ms/op
                 getUser·p0.95:   6.054 ms/op
                 getUser·p0.99:   7.905 ms/op
                 getUser·p0.999:  10.958 ms/op
                 getUser·p0.9999: 19.679 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   3: 4.324 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.358 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   7.315 ms/op
                 getUser·p0.999:  11.176 ms/op
                 getUser·p0.9999: 20.343 ms/op
                 getUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221955
  mean =      4.326 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4937 
    [ 2.500,  5.000) = 175636 
    [ 5.000,  7.500) = 38916 
    [ 7.500, 10.000) = 1957 
    [10.000, 12.500) = 330 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.423 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      7.643 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     21.549 ms/op
     p(99.9990) =     22.825 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.623 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 5.864 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.650 ±(99.9%) 0.021 ms/op
Iteration   1: 5.586 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   5.300 ms/op
                 listUser·p0.90:   7.250 ms/op
                 listUser·p0.95:   8.274 ms/op
                 listUser·p0.99:   10.589 ms/op
                 listUser·p0.999:  16.722 ms/op
                 listUser·p0.9999: 20.334 ms/op
                 listUser·p1.00:   20.840 ms/op

Iteration   2: 5.953 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   5.554 ms/op
                 listUser·p0.90:   8.053 ms/op
                 listUser·p0.95:   9.110 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  20.784 ms/op
                 listUser·p0.9999: 23.880 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   3: 5.812 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.460 ms/op
                 listUser·p0.50:   5.423 ms/op
                 listUser·p0.90:   7.815 ms/op
                 listUser·p0.95:   8.946 ms/op
                 listUser·p0.99:   11.780 ms/op
                 listUser·p0.999:  22.226 ms/op
                 listUser·p0.9999: 28.998 ms/op
                 listUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 166090
  mean =      5.780 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 111 
    [ 2.500,  5.000) = 54051 
    [ 5.000,  7.500) = 92771 
    [ 7.500, 10.000) = 15158 
    [10.000, 12.500) = 3035 
    [12.500, 15.000) = 493 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      7.725 ms/op
     p(95.0000) =      8.798 ms/op
     p(99.0000) =     11.485 ms/op
     p(99.9000) =     20.185 ms/op
     p(99.9900) =     27.210 ms/op
     p(99.9990) =     29.547 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.086 ± 2.539  ops/ms
ClientGrpc.existUser                       thrpt       3   7.764 ± 2.059  ops/ms
ClientGrpc.getUser                         thrpt       3   7.181 ± 2.859  ops/ms
ClientGrpc.listUser                        thrpt       3   5.434 ± 1.747  ops/ms
ClientGrpc.createUser                       avgt       3   4.445 ± 0.379   ms/op
ClientGrpc.existUser                        avgt       3   4.207 ± 0.826   ms/op
ClientGrpc.getUser                          avgt       3   4.491 ± 1.537   ms/op
ClientGrpc.listUser                         avgt       3   5.666 ± 2.736   ms/op
ClientGrpc.createUser                     sample  221852   4.327 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.065           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.472           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.997           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.885           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.044           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.047           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.757           ms/op
ClientGrpc.existUser                      sample  230191   4.168 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.360           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.055           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.177           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.661           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.487           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.780           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.156           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.669           ms/op
ClientGrpc.getUser                        sample  221955   4.326 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.693           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.423           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.906           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.643           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.567           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.549           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.872           ms/op
ClientGrpc.listUser                       sample  166090   5.780 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.202           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.423           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.725           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.798           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.485           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.185           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.210           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.655           ms/op
