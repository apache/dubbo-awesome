# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.698 ops/ms
# Warmup Iteration   2: 3.893 ops/ms
# Warmup Iteration   3: 7.454 ops/ms
Iteration   1: 7.605 ops/ms
Iteration   2: 8.112 ops/ms
Iteration   3: 7.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.817 ±(99.9%) 4.811 ops/ms [Average]
  (min, avg, max) = (7.605, 7.817, 8.112), stdev = 0.264
  CI (99.9%): [3.005, 12.628] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.208 ops/ms
# Warmup Iteration   2: 6.267 ops/ms
# Warmup Iteration   3: 8.046 ops/ms
Iteration   1: 8.156 ops/ms
Iteration   2: 8.294 ops/ms
Iteration   3: 8.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.295 ±(99.9%) 2.533 ops/ms [Average]
  (min, avg, max) = (8.156, 8.295, 8.434), stdev = 0.139
  CI (99.9%): [5.761, 10.828] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.120 ops/ms
# Warmup Iteration   2: 6.468 ops/ms
# Warmup Iteration   3: 7.935 ops/ms
Iteration   1: 7.948 ops/ms
Iteration   2: 7.961 ops/ms
Iteration   3: 7.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.895 ±(99.9%) 1.902 ops/ms [Average]
  (min, avg, max) = (7.775, 7.895, 7.961), stdev = 0.104
  CI (99.9%): [5.993, 9.797] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.092 ops/ms
# Warmup Iteration   2: 5.527 ops/ms
# Warmup Iteration   3: 6.516 ops/ms
Iteration   1: 6.654 ops/ms
Iteration   2: 7.068 ops/ms
Iteration   3: 6.866 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.863 ±(99.9%) 3.783 ops/ms [Average]
  (min, avg, max) = (6.654, 6.863, 7.068), stdev = 0.207
  CI (99.9%): [3.080, 10.645] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 13.545 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 4.732 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.144 ±(99.9%) 0.011 ms/op
Iteration   1: 4.130 ±(99.9%) 0.006 ms/op
Iteration   2: 3.923 ±(99.9%) 0.010 ms/op
Iteration   3: 3.953 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.002 ±(99.9%) 2.039 ms/op [Average]
  (min, avg, max) = (3.923, 4.002, 4.130), stdev = 0.112
  CI (99.9%): [1.963, 6.041] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.074 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.328 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.009 ms/op
Iteration   1: 3.803 ±(99.9%) 0.003 ms/op
Iteration   2: 3.742 ±(99.9%) 0.007 ms/op
Iteration   3: 3.666 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.737 ±(99.9%) 1.250 ms/op [Average]
  (min, avg, max) = (3.666, 3.737, 3.803), stdev = 0.069
  CI (99.9%): [2.487, 4.988] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.842 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.966 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.009 ms/op
Iteration   1: 3.863 ±(99.9%) 0.008 ms/op
Iteration   2: 3.981 ±(99.9%) 0.011 ms/op
Iteration   3: 3.857 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.901 ±(99.9%) 1.275 ms/op [Average]
  (min, avg, max) = (3.857, 3.901, 3.981), stdev = 0.070
  CI (99.9%): [2.625, 5.176] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.412 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.255 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.617 ±(99.9%) 0.012 ms/op
Iteration   1: 4.587 ±(99.9%) 0.008 ms/op
Iteration   2: 4.403 ±(99.9%) 0.014 ms/op
Iteration   3: 4.445 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.478 ±(99.9%) 1.753 ms/op [Average]
  (min, avg, max) = (4.403, 4.478, 4.587), stdev = 0.096
  CI (99.9%): [2.725, 6.231] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.607 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.943 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.276 ±(99.9%) 0.017 ms/op
Iteration   1: 4.052 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.921 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   7.168 ms/op
                 createUser·p0.999:  14.074 ms/op
                 createUser·p0.9999: 31.850 ms/op
                 createUser·p1.00:   32.342 ms/op

Iteration   2: 4.125 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   5.054 ms/op
                 createUser·p0.95:   5.554 ms/op
                 createUser·p0.99:   7.184 ms/op
                 createUser·p0.999:  28.049 ms/op
                 createUser·p0.9999: 35.324 ms/op
                 createUser·p1.00:   37.945 ms/op

Iteration   3: 3.936 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   5.530 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  20.906 ms/op
                 createUser·p0.9999: 32.268 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237859
  mean =      4.036 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 510 
    [ 2.500,  5.000) = 219007 
    [ 5.000,  7.500) = 16682 
    [ 7.500, 10.000) = 1152 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 104 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     23.167 ms/op
     p(99.9900) =     33.529 ms/op
     p(99.9990) =     35.643 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.587 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
Iteration   1: 3.768 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.678 ms/op
                 existUser·p0.99:   6.185 ms/op
                 existUser·p0.999:  23.466 ms/op
                 existUser·p0.9999: 31.130 ms/op
                 existUser·p1.00:   32.276 ms/op

Iteration   2: 3.822 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.839 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.157 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   7.528 ms/op
                 existUser·p0.999:  16.167 ms/op
                 existUser·p0.9999: 27.108 ms/op
                 existUser·p1.00:   28.148 ms/op

Iteration   3: 3.773 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  28.121 ms/op
                 existUser·p0.9999: 31.296 ms/op
                 existUser·p1.00:   33.161 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 253301
  mean =      3.788 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 242 
    [ 2.500,  5.000) = 245392 
    [ 5.000,  7.500) = 6086 
    [ 7.500, 10.000) = 810 
    [10.000, 12.500) = 379 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     23.127 ms/op
     p(99.9900) =     30.955 ms/op
     p(99.9990) =     31.997 ms/op
     p(99.9999) =     33.161 ms/op
    p(100.0000) =     33.161 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.441 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.159 ±(99.9%) 0.015 ms/op
Iteration   1: 3.882 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   2.101 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  11.873 ms/op
                 getUser·p0.9999: 25.095 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   2: 3.856 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.511 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  24.184 ms/op
                 getUser·p0.9999: 27.981 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 3.918 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.782 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.701 ms/op
                 getUser·p0.999:  12.892 ms/op
                 getUser·p0.9999: 29.147 ms/op
                 getUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 247011
  mean =      3.885 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 68 
    [ 2.500,  5.000) = 240877 
    [ 5.000,  7.500) = 4623 
    [ 7.500, 10.000) = 1005 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 100 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.511 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     12.845 ms/op
     p(99.9900) =     28.049 ms/op
     p(99.9990) =     29.717 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.876 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 5.347 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.858 ±(99.9%) 0.020 ms/op
Iteration   1: 4.600 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.870 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  25.126 ms/op
                 listUser·p0.9999: 29.888 ms/op
                 listUser·p1.00:   30.605 ms/op

Iteration   2: 4.512 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.421 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.210 ms/op
                 listUser·p0.99:   7.993 ms/op
                 listUser·p0.999:  18.317 ms/op
                 listUser·p0.9999: 24.510 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   3: 4.576 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   8.671 ms/op
                 listUser·p0.999:  18.907 ms/op
                 listUser·p0.9999: 23.430 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 210395
  mean =      4.563 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 189105 
    [ 5.000,  7.500) = 17250 
    [ 7.500, 10.000) = 2968 
    [10.000, 12.500) = 536 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.870 ms/op
     p(50.0000) =      4.366 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      8.552 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     27.975 ms/op
     p(99.9990) =     30.598 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.817 ± 4.811  ops/ms
ClientPb.existUser                       thrpt       3   8.295 ± 2.533  ops/ms
ClientPb.getUser                         thrpt       3   7.895 ± 1.902  ops/ms
ClientPb.listUser                        thrpt       3   6.863 ± 3.783  ops/ms
ClientPb.createUser                       avgt       3   4.002 ± 2.039   ms/op
ClientPb.existUser                        avgt       3   3.737 ± 1.250   ms/op
ClientPb.getUser                          avgt       3   3.901 ± 1.275   ms/op
ClientPb.listUser                         avgt       3   4.478 ± 1.753   ms/op
ClientPb.createUser                     sample  237859   4.036 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.206           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.825           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.102           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.167           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.529           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.945           ms/op
ClientPb.existUser                      sample  253301   3.788 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.448           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.670           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.182           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.555           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.545           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.127           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.955           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.161           ms/op
ClientPb.getUser                        sample  247011   3.885 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.511           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.260           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.570           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.845           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.049           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.409           ms/op
ClientPb.listUser                       sample  210395   4.563 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.870           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.341           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.120           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.975           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.605           ms/op
