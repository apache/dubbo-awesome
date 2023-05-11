# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.316 ops/ms
# Warmup Iteration   2: 6.107 ops/ms
# Warmup Iteration   3: 7.351 ops/ms
Iteration   1: 7.910 ops/ms
Iteration   2: 7.880 ops/ms
Iteration   3: 7.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.875 ±(99.9%) 0.692 ops/ms [Average]
  (min, avg, max) = (7.835, 7.875, 7.910), stdev = 0.038
  CI (99.9%): [7.183, 8.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.738 ops/ms
# Warmup Iteration   2: 7.728 ops/ms
# Warmup Iteration   3: 8.486 ops/ms
Iteration   1: 8.399 ops/ms
Iteration   2: 8.895 ops/ms
Iteration   3: 8.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.720 ±(99.9%) 5.086 ops/ms [Average]
  (min, avg, max) = (8.399, 8.720, 8.895), stdev = 0.279
  CI (99.9%): [3.635, 13.806] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.281 ops/ms
# Warmup Iteration   2: 7.107 ops/ms
# Warmup Iteration   3: 7.476 ops/ms
Iteration   1: 8.005 ops/ms
Iteration   2: 7.896 ops/ms
Iteration   3: 7.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.873 ±(99.9%) 2.652 ops/ms [Average]
  (min, avg, max) = (7.717, 7.873, 8.005), stdev = 0.145
  CI (99.9%): [5.220, 10.525] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.777 ops/ms
# Warmup Iteration   2: 5.749 ops/ms
# Warmup Iteration   3: 6.234 ops/ms
Iteration   1: 6.216 ops/ms
Iteration   2: 6.278 ops/ms
Iteration   3: 6.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.237 ±(99.9%) 0.649 ops/ms [Average]
  (min, avg, max) = (6.216, 6.237, 6.278), stdev = 0.036
  CI (99.9%): [5.588, 6.886] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.553 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.385 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.003 ms/op
Iteration   1: 4.074 ±(99.9%) 0.003 ms/op
Iteration   2: 4.000 ±(99.9%) 0.003 ms/op
Iteration   3: 4.001 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.025 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (4.000, 4.025, 4.074), stdev = 0.042
  CI (99.9%): [3.254, 4.796] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.370 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.003 ms/op
Iteration   1: 3.539 ±(99.9%) 0.004 ms/op
Iteration   2: 3.679 ±(99.9%) 0.003 ms/op
Iteration   3: 3.685 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.634 ±(99.9%) 1.511 ms/op [Average]
  (min, avg, max) = (3.539, 3.634, 3.685), stdev = 0.083
  CI (99.9%): [2.124, 5.145] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.171 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.899 ±(99.9%) 0.003 ms/op
Iteration   2: 4.013 ±(99.9%) 0.003 ms/op
Iteration   3: 3.873 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.928 ±(99.9%) 1.365 ms/op [Average]
  (min, avg, max) = (3.873, 3.928, 4.013), stdev = 0.075
  CI (99.9%): [2.564, 5.293] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.804 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.578 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.155 ±(99.9%) 0.022 ms/op
Iteration   1: 5.033 ±(99.9%) 0.016 ms/op
Iteration   2: 5.154 ±(99.9%) 0.019 ms/op
Iteration   3: 5.108 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.099 ±(99.9%) 1.117 ms/op [Average]
  (min, avg, max) = (5.033, 5.099, 5.154), stdev = 0.061
  CI (99.9%): [3.982, 6.216] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.114 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.342 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.011 ms/op
Iteration   1: 3.952 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.809 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  10.195 ms/op
                 createUser·p0.9999: 25.026 ms/op
                 createUser·p1.00:   25.461 ms/op

Iteration   2: 3.962 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.382 ms/op
                 createUser·p0.99:   6.710 ms/op
                 createUser·p0.999:  12.686 ms/op
                 createUser·p0.9999: 15.236 ms/op
                 createUser·p1.00:   16.433 ms/op

Iteration   3: 4.061 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   3.928 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.366 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  17.236 ms/op
                 createUser·p0.9999: 29.594 ms/op
                 createUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 240456
  mean =      3.991 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6212 
    [ 2.500,  5.000) = 213765 
    [ 5.000,  7.500) = 18942 
    [ 7.500, 10.000) = 1027 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.317 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.470 ms/op
     p(99.9900) =     28.046 ms/op
     p(99.9990) =     30.290 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.846 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.011 ms/op
Iteration   1: 3.880 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.768 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  9.693 ms/op
                 existUser·p0.9999: 16.176 ms/op
                 existUser·p1.00:   16.515 ms/op

Iteration   2: 3.748 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.027 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  10.905 ms/op
                 existUser·p0.9999: 17.641 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   3: 3.738 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.456 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   4.489 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   6.840 ms/op
                 existUser·p0.999:  12.867 ms/op
                 existUser·p0.9999: 21.543 ms/op
                 existUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 253379
  mean =      3.788 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6334 
    [ 2.500,  5.000) = 233034 
    [ 5.000,  7.500) = 12581 
    [ 7.500, 10.000) = 1069 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      6.629 ms/op
     p(99.9000) =     11.141 ms/op
     p(99.9900) =     20.523 ms/op
     p(99.9990) =     23.248 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.224 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.297 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.011 ms/op
Iteration   1: 3.961 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  12.373 ms/op
                 getUser·p0.9999: 15.542 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   2: 3.935 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  14.229 ms/op
                 getUser·p0.9999: 20.865 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   3: 4.044 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   6.727 ms/op
                 getUser·p0.999:  11.026 ms/op
                 getUser·p0.9999: 21.371 ms/op
                 getUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 241153
  mean =      3.980 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9840 
    [ 2.500,  5.000) = 210623 
    [ 5.000,  7.500) = 18729 
    [ 7.500, 10.000) = 1335 
    [10.000, 12.500) = 425 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     11.974 ms/op
     p(99.9900) =     20.735 ms/op
     p(99.9990) =     22.662 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.955 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.385 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.113 ±(99.9%) 0.017 ms/op
Iteration   1: 5.177 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.532 ms/op
                 listUser·p0.50:   4.858 ms/op
                 listUser·p0.90:   7.078 ms/op
                 listUser·p0.95:   7.848 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  20.283 ms/op
                 listUser·p0.9999: 26.077 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   2: 5.104 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.872 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.898 ms/op
                 listUser·p0.95:   7.881 ms/op
                 listUser·p0.99:   10.437 ms/op
                 listUser·p0.999:  16.886 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 5.183 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   4.891 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.733 ms/op
                 listUser·p0.99:   10.387 ms/op
                 listUser·p0.999:  26.585 ms/op
                 listUser·p0.9999: 30.764 ms/op
                 listUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 186226
  mean =      5.154 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 381 
    [ 2.500,  5.000) = 105426 
    [ 5.000,  7.500) = 68169 
    [ 7.500, 10.000) = 10173 
    [10.000, 12.500) = 1390 
    [12.500, 15.000) = 313 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.423 ms/op
     p(50.0000) =      4.850 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      7.832 ms/op
     p(99.0000) =     10.191 ms/op
     p(99.9000) =     19.686 ms/op
     p(99.9900) =     29.758 ms/op
     p(99.9990) =     30.932 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.875 ± 0.692  ops/ms
ClientGrpc.existUser                       thrpt       3   8.720 ± 5.086  ops/ms
ClientGrpc.getUser                         thrpt       3   7.873 ± 2.652  ops/ms
ClientGrpc.listUser                        thrpt       3   6.237 ± 0.649  ops/ms
ClientGrpc.createUser                       avgt       3   4.025 ± 0.771   ms/op
ClientGrpc.existUser                        avgt       3   3.634 ± 1.511   ms/op
ClientGrpc.getUser                          avgt       3   3.928 ± 1.365   ms/op
ClientGrpc.listUser                         avgt       3   5.099 ± 1.117   ms/op
ClientGrpc.createUser                     sample  240456   3.991 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.965           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.317           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.717           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.470           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.046           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.376           ms/op
ClientGrpc.existUser                      sample  253379   3.788 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.456           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.063           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.629           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.141           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.523           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.364           ms/op
ClientGrpc.getUser                        sample  241153   3.980 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.887           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.915           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.341           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.021           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.974           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.735           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.331           ms/op
ClientGrpc.listUser                       sample  186226   5.154 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.423           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.832           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.191           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.686           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.758           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.130           ms/op
