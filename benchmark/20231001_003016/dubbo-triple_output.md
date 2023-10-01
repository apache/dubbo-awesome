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
# Warmup Iteration   1: 2.395 ops/ms
# Warmup Iteration   2: 6.300 ops/ms
# Warmup Iteration   3: 8.946 ops/ms
Iteration   1: 9.738 ops/ms
Iteration   2: 9.928 ops/ms
Iteration   3: 9.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.847 ±(99.9%) 1.792 ops/ms [Average]
  (min, avg, max) = (9.738, 9.847, 9.928), stdev = 0.098
  CI (99.9%): [8.055, 11.639] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.292 ops/ms
# Warmup Iteration   2: 9.536 ops/ms
# Warmup Iteration   3: 9.854 ops/ms
Iteration   1: 10.338 ops/ms
Iteration   2: 10.352 ops/ms
Iteration   3: 10.206 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.299 ±(99.9%) 1.474 ops/ms [Average]
  (min, avg, max) = (10.206, 10.299, 10.352), stdev = 0.081
  CI (99.9%): [8.824, 11.773] (assumes normal distribution)


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
# Warmup Iteration   1: 3.152 ops/ms
# Warmup Iteration   2: 8.956 ops/ms
# Warmup Iteration   3: 9.762 ops/ms
Iteration   1: 9.893 ops/ms
Iteration   2: 9.893 ops/ms
Iteration   3: 9.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.876 ±(99.9%) 0.523 ops/ms [Average]
  (min, avg, max) = (9.843, 9.876, 9.893), stdev = 0.029
  CI (99.9%): [9.353, 10.400] (assumes normal distribution)


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
# Warmup Iteration   1: 3.673 ops/ms
# Warmup Iteration   2: 7.974 ops/ms
# Warmup Iteration   3: 8.388 ops/ms
Iteration   1: 8.193 ops/ms
Iteration   2: 8.420 ops/ms
Iteration   3: 8.358 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.323 ±(99.9%) 2.137 ops/ms [Average]
  (min, avg, max) = (8.193, 8.323, 8.420), stdev = 0.117
  CI (99.9%): [6.186, 10.460] (assumes normal distribution)


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
# Warmup Iteration   1: 8.945 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.345 ±(99.9%) 0.003 ms/op
Iteration   1: 3.259 ±(99.9%) 0.003 ms/op
Iteration   2: 3.227 ±(99.9%) 0.006 ms/op
Iteration   3: 3.262 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.249 ±(99.9%) 0.353 ms/op [Average]
  (min, avg, max) = (3.227, 3.249, 3.262), stdev = 0.019
  CI (99.9%): [2.897, 3.602] (assumes normal distribution)


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
# Warmup Iteration   1: 8.234 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.359 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.001 ms/op
Iteration   1: 3.162 ±(99.9%) 0.002 ms/op
Iteration   2: 3.124 ±(99.9%) 0.004 ms/op
Iteration   3: 3.118 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.134 ±(99.9%) 0.441 ms/op [Average]
  (min, avg, max) = (3.118, 3.134, 3.162), stdev = 0.024
  CI (99.9%): [2.693, 3.576] (assumes normal distribution)


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
# Warmup Iteration   1: 7.375 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.002 ms/op
Iteration   1: 3.224 ±(99.9%) 0.004 ms/op
Iteration   2: 3.200 ±(99.9%) 0.003 ms/op
Iteration   3: 3.300 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.242 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (3.200, 3.242, 3.300), stdev = 0.052
  CI (99.9%): [2.285, 4.198] (assumes normal distribution)


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
# Warmup Iteration   1: 8.588 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.003 ms/op
Iteration   1: 3.901 ±(99.9%) 0.005 ms/op
Iteration   2: 3.898 ±(99.9%) 0.005 ms/op
Iteration   3: 3.869 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.889 ±(99.9%) 0.320 ms/op [Average]
  (min, avg, max) = (3.869, 3.889, 3.901), stdev = 0.018
  CI (99.9%): [3.569, 4.209] (assumes normal distribution)


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
# Warmup Iteration   1: 8.084 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.009 ms/op
Iteration   1: 3.259 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.227 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  15.970 ms/op
                 createUser·p0.9999: 18.973 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   2: 3.246 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  16.073 ms/op
                 createUser·p0.9999: 20.485 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   3: 3.251 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   6.165 ms/op
                 createUser·p0.999:  13.730 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295104
  mean =      3.252 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15052 
    [ 2.500,  5.000) = 274815 
    [ 5.000,  7.500) = 4425 
    [ 7.500, 10.000) = 251 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 168 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     14.786 ms/op
     p(99.9900) =     19.873 ms/op
     p(99.9990) =     21.148 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


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
# Warmup Iteration   1: 7.059 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.007 ms/op
Iteration   1: 3.208 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.210 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  15.037 ms/op
                 existUser·p0.9999: 18.516 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  16.159 ms/op
                 existUser·p0.9999: 20.120 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   3: 3.196 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  10.696 ms/op
                 existUser·p0.9999: 20.708 ms/op
                 existUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299801
  mean =      3.201 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19332 
    [ 2.500,  5.000) = 275961 
    [ 5.000,  7.500) = 3682 
    [ 7.500, 10.000) = 234 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 151 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 9.458 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.008 ms/op
Iteration   1: 3.332 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  15.638 ms/op
                 getUser·p0.9999: 18.874 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   2: 3.319 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.081 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   6.117 ms/op
                 getUser·p0.999:  17.487 ms/op
                 getUser·p0.9999: 22.753 ms/op
                 getUser·p1.00:   23.101 ms/op

Iteration   3: 3.322 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.405 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  13.137 ms/op
                 getUser·p0.9999: 20.472 ms/op
                 getUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 288758
  mean =      3.324 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6472 
    [ 2.500,  5.000) = 275239 
    [ 5.000,  7.500) = 6059 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     14.786 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     22.981 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 8.990 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.172 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.011 ms/op
Iteration   1: 3.872 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.833 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  15.892 ms/op
                 listUser·p0.9999: 20.217 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 3.822 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   6.608 ms/op
                 listUser·p0.999:  12.894 ms/op
                 listUser·p0.9999: 14.142 ms/op
                 listUser·p1.00:   15.385 ms/op

Iteration   3: 3.883 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.274 ms/op
                 listUser·p0.9999: 15.984 ms/op
                 listUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248549
  mean =      3.859 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 241909 
    [ 5.000,  7.500) = 5038 
    [ 7.500, 10.000) = 759 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 345 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     13.409 ms/op
     p(99.9900) =     19.474 ms/op
     p(99.9990) =     20.464 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.847 ± 1.792  ops/ms
ClientPb.existUser                       thrpt       3  10.299 ± 1.474  ops/ms
ClientPb.getUser                         thrpt       3   9.876 ± 0.523  ops/ms
ClientPb.listUser                        thrpt       3   8.323 ± 2.137  ops/ms
ClientPb.createUser                       avgt       3   3.249 ± 0.353   ms/op
ClientPb.existUser                        avgt       3   3.134 ± 0.441   ms/op
ClientPb.getUser                          avgt       3   3.242 ± 0.957   ms/op
ClientPb.listUser                         avgt       3   3.889 ± 0.320   ms/op
ClientPb.createUser                     sample  295104   3.252 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.098           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.702           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.786           ms/op
ClientPb.createUser:createUser·p0.9999  sample          19.873           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.561           ms/op
ClientPb.existUser                      sample  299801   3.201 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.968           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.740           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.554           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.517           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.087           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.103           ms/op
ClientPb.getUser                        sample  288758   3.324 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.966           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.211           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.439           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.786           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.627           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.101           ms/op
ClientPb.listUser                       sample  248549   3.859 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.569           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.752           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.726           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.409           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.474           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.546           ms/op
