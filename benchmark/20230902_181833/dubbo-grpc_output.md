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
# Warmup Iteration   1: 4.668 ops/ms
# Warmup Iteration   2: 9.227 ops/ms
# Warmup Iteration   3: 10.210 ops/ms
Iteration   1: 10.618 ops/ms
Iteration   2: 10.909 ops/ms
Iteration   3: 10.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.759 ±(99.9%) 2.663 ops/ms [Average]
  (min, avg, max) = (10.618, 10.759, 10.909), stdev = 0.146
  CI (99.9%): [8.096, 13.422] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.698 ops/ms
# Warmup Iteration   2: 11.052 ops/ms
# Warmup Iteration   3: 11.141 ops/ms
Iteration   1: 11.332 ops/ms
Iteration   2: 11.159 ops/ms
Iteration   3: 11.391 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.294 ±(99.9%) 2.195 ops/ms [Average]
  (min, avg, max) = (11.159, 11.294, 11.391), stdev = 0.120
  CI (99.9%): [9.099, 13.489] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.320 ops/ms
# Warmup Iteration   2: 10.326 ops/ms
# Warmup Iteration   3: 10.592 ops/ms
Iteration   1: 10.845 ops/ms
Iteration   2: 10.438 ops/ms
Iteration   3: 10.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.701 ±(99.9%) 4.172 ops/ms [Average]
  (min, avg, max) = (10.438, 10.701, 10.845), stdev = 0.229
  CI (99.9%): [6.529, 14.874] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.690 ops/ms
# Warmup Iteration   2: 8.076 ops/ms
# Warmup Iteration   3: 8.195 ops/ms
Iteration   1: 8.482 ops/ms
Iteration   2: 8.258 ops/ms
Iteration   3: 8.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.345 ±(99.9%) 2.189 ops/ms [Average]
  (min, avg, max) = (8.258, 8.345, 8.482), stdev = 0.120
  CI (99.9%): [6.156, 10.534] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.847 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.003 ms/op
Iteration   2: 2.970 ±(99.9%) 0.003 ms/op
Iteration   3: 2.971 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.967 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (2.961, 2.967, 2.971), stdev = 0.006
  CI (99.9%): [2.865, 3.069] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.777 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.861 ±(99.9%) 0.004 ms/op
Iteration   1: 2.875 ±(99.9%) 0.004 ms/op
Iteration   2: 2.917 ±(99.9%) 0.002 ms/op
Iteration   3: 2.891 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.894 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (2.875, 2.894, 2.917), stdev = 0.021
  CI (99.9%): [2.512, 3.277] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.043 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.002 ms/op
Iteration   1: 2.957 ±(99.9%) 0.003 ms/op
Iteration   2: 2.990 ±(99.9%) 0.002 ms/op
Iteration   3: 2.951 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.966 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (2.951, 2.966, 2.990), stdev = 0.021
  CI (99.9%): [2.585, 3.347] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.211 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.907 ±(99.9%) 0.027 ms/op
Iteration   1: 3.763 ±(99.9%) 0.011 ms/op
Iteration   2: 3.834 ±(99.9%) 0.028 ms/op
Iteration   3: 3.840 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.812 ±(99.9%) 0.782 ms/op [Average]
  (min, avg, max) = (3.763, 3.812, 3.840), stdev = 0.043
  CI (99.9%): [3.031, 4.594] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.003 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.007 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.927 ms/op
                 createUser·p0.9999: 13.466 ms/op
                 createUser·p1.00:   13.664 ms/op

Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  8.299 ms/op
                 createUser·p0.9999: 15.106 ms/op
                 createUser·p1.00:   15.499 ms/op

Iteration   3: 2.978 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  9.585 ms/op
                 createUser·p0.9999: 17.997 ms/op
                 createUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320210
  mean =      2.998 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1558 
    [ 1.250,  2.500) = 28770 
    [ 2.500,  3.750) = 273888 
    [ 3.750,  5.000) = 14192 
    [ 5.000,  6.250) = 938 
    [ 6.250,  7.500) = 313 
    [ 7.500,  8.750) = 192 
    [ 8.750, 10.000) = 113 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.637 ms/op
     p(99.9000) =      9.254 ms/op
     p(99.9900) =     15.595 ms/op
     p(99.9990) =     18.599 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.423 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.907 ±(99.9%) 0.006 ms/op
Iteration   1: 2.856 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  7.455 ms/op
                 existUser·p0.9999: 17.269 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 2.846 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  7.312 ms/op
                 existUser·p0.9999: 12.985 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   3: 2.892 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  7.581 ms/op
                 existUser·p0.9999: 14.415 ms/op
                 existUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335060
  mean =      2.864 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3773 
    [ 1.250,  2.500) = 45836 
    [ 2.500,  3.750) = 275319 
    [ 3.750,  5.000) = 8594 
    [ 5.000,  6.250) = 845 
    [ 6.250,  7.500) = 373 
    [ 7.500,  8.750) = 158 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.455 ms/op
     p(99.9900) =     14.844 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.903 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 2.984 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  7.954 ms/op
                 getUser·p0.9999: 14.947 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   2: 3.031 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.757 ms/op
                 getUser·p0.99:   4.516 ms/op
                 getUser·p0.999:  8.031 ms/op
                 getUser·p0.9999: 26.345 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.557 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.434 ms/op
                 getUser·p0.9999: 18.186 ms/op
                 getUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320640
  mean =      2.994 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27797 
    [ 2.500,  5.000) = 290899 
    [ 5.000,  7.500) = 1538 
    [ 7.500, 10.000) = 214 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.908 ms/op
     p(99.9900) =     25.160 ms/op
     p(99.9990) =     26.797 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.430 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.827 ±(99.9%) 0.011 ms/op
Iteration   1: 3.857 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.766 ms/op
                 listUser·p0.999:  14.483 ms/op
                 listUser·p0.9999: 19.979 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   2: 3.864 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.745 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.157 ms/op
                 listUser·p0.9999: 23.200 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   3: 3.911 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.274 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  15.236 ms/op
                 listUser·p0.9999: 24.379 ms/op
                 listUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247649
  mean =      3.877 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5098 
    [ 2.500,  5.000) = 221064 
    [ 5.000,  7.500) = 20048 
    [ 7.500, 10.000) = 899 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.274 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     15.161 ms/op
     p(99.9900) =     22.855 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.759 ± 2.663  ops/ms
ClientGrpc.existUser                       thrpt       3  11.294 ± 2.195  ops/ms
ClientGrpc.getUser                         thrpt       3  10.701 ± 4.172  ops/ms
ClientGrpc.listUser                        thrpt       3   8.345 ± 2.189  ops/ms
ClientGrpc.createUser                       avgt       3   2.967 ± 0.102   ms/op
ClientGrpc.existUser                        avgt       3   2.894 ± 0.382   ms/op
ClientGrpc.getUser                          avgt       3   2.966 ± 0.381   ms/op
ClientGrpc.listUser                         avgt       3   3.812 ± 0.782   ms/op
ClientGrpc.createUser                     sample  320210   2.998 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.628           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.637           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.254           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.595           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.711           ms/op
ClientGrpc.existUser                      sample  335060   2.864 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.631           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.455           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.844           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.695           ms/op
ClientGrpc.getUser                        sample  320640   2.994 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.557           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.908           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.160           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.837           ms/op
ClientGrpc.listUser                       sample  247649   3.877 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.274           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.161           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.855           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.723           ms/op
