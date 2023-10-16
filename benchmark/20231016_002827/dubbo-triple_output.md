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
# Warmup Iteration   1: 2.454 ops/ms
# Warmup Iteration   2: 5.984 ops/ms
# Warmup Iteration   3: 9.055 ops/ms
Iteration   1: 9.728 ops/ms
Iteration   2: 9.604 ops/ms
Iteration   3: 9.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.626 ±(99.9%) 1.688 ops/ms [Average]
  (min, avg, max) = (9.547, 9.626, 9.728), stdev = 0.093
  CI (99.9%): [7.938, 11.314] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.329 ops/ms
# Warmup Iteration   2: 9.063 ops/ms
# Warmup Iteration   3: 9.977 ops/ms
Iteration   1: 10.080 ops/ms
Iteration   2: 10.204 ops/ms
Iteration   3: 10.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.102 ±(99.9%) 1.682 ops/ms [Average]
  (min, avg, max) = (10.023, 10.102, 10.204), stdev = 0.092
  CI (99.9%): [8.421, 11.784] (assumes normal distribution)


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
# Warmup Iteration   1: 3.379 ops/ms
# Warmup Iteration   2: 8.970 ops/ms
# Warmup Iteration   3: 9.739 ops/ms
Iteration   1: 9.696 ops/ms
Iteration   2: 9.935 ops/ms
Iteration   3: 9.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.809 ±(99.9%) 2.189 ops/ms [Average]
  (min, avg, max) = (9.696, 9.809, 9.935), stdev = 0.120
  CI (99.9%): [7.620, 11.999] (assumes normal distribution)


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
# Warmup Iteration   1: 3.204 ops/ms
# Warmup Iteration   2: 7.666 ops/ms
# Warmup Iteration   3: 8.128 ops/ms
Iteration   1: 8.432 ops/ms
Iteration   2: 8.055 ops/ms
Iteration   3: 8.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.323 ±(99.9%) 4.267 ops/ms [Average]
  (min, avg, max) = (8.055, 8.323, 8.484), stdev = 0.234
  CI (99.9%): [4.056, 12.590] (assumes normal distribution)


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
# Warmup Iteration   1: 8.783 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.437 ±(99.9%) 0.007 ms/op
Iteration   1: 3.313 ±(99.9%) 0.005 ms/op
Iteration   2: 3.274 ±(99.9%) 0.004 ms/op
Iteration   3: 3.345 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.311 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (3.274, 3.311, 3.345), stdev = 0.035
  CI (99.9%): [2.663, 3.958] (assumes normal distribution)


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
# Warmup Iteration   1: 7.611 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.002 ms/op
Iteration   1: 3.137 ±(99.9%) 0.004 ms/op
Iteration   2: 3.181 ±(99.9%) 0.003 ms/op
Iteration   3: 3.157 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.159 ±(99.9%) 0.400 ms/op [Average]
  (min, avg, max) = (3.137, 3.159, 3.181), stdev = 0.022
  CI (99.9%): [2.758, 3.559] (assumes normal distribution)


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
# Warmup Iteration   1: 7.981 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.003 ms/op
Iteration   1: 3.238 ±(99.9%) 0.002 ms/op
Iteration   2: 3.306 ±(99.9%) 0.004 ms/op
Iteration   3: 3.242 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.262 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (3.238, 3.262, 3.306), stdev = 0.038
  CI (99.9%): [2.566, 3.958] (assumes normal distribution)


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
# Warmup Iteration   1: 9.271 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.004 ms/op
Iteration   1: 3.834 ±(99.9%) 0.004 ms/op
Iteration   2: 3.852 ±(99.9%) 0.007 ms/op
Iteration   3: 3.881 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.856 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (3.834, 3.856, 3.881), stdev = 0.024
  CI (99.9%): [3.419, 4.292] (assumes normal distribution)


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
# Warmup Iteration   1: 8.741 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.008 ms/op
Iteration   1: 3.392 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.279 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.431 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  15.777 ms/op
                 createUser·p0.9999: 19.089 ms/op
                 createUser·p1.00:   21.725 ms/op

Iteration   2: 3.337 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.031 ms/op
                 createUser·p0.99:   5.841 ms/op
                 createUser·p0.999:  18.399 ms/op
                 createUser·p0.9999: 34.800 ms/op
                 createUser·p1.00:   38.142 ms/op

Iteration   3: 3.318 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.777 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   4.122 ms/op
                 createUser·p0.99:   6.671 ms/op
                 createUser·p0.999:  17.620 ms/op
                 createUser·p0.9999: 25.734 ms/op
                 createUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286804
  mean =      3.349 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10285 
    [ 2.500,  5.000) = 268688 
    [ 5.000,  7.500) = 6674 
    [ 7.500, 10.000) = 476 
    [10.000, 12.500) = 239 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 129 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.279 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.157 ms/op
     p(99.0000) =      6.365 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     31.107 ms/op
     p(99.9990) =     35.014 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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
# Warmup Iteration   1: 7.635 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.009 ms/op
Iteration   1: 3.130 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.245 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  18.153 ms/op
                 existUser·p0.9999: 20.531 ms/op
                 existUser·p1.00:   21.070 ms/op

Iteration   2: 3.175 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.450 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  18.457 ms/op
                 existUser·p0.9999: 22.441 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   3: 3.266 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.951 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  15.327 ms/op
                 existUser·p0.9999: 22.807 ms/op
                 existUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300905
  mean =      3.189 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20693 
    [ 2.500,  5.000) = 273893 
    [ 5.000,  7.500) = 4956 
    [ 7.500, 10.000) = 749 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 157 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      6.275 ms/op
     p(99.9000) =     15.927 ms/op
     p(99.9900) =     22.443 ms/op
     p(99.9990) =     23.297 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 8.559 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.461 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.011 ms/op
Iteration   1: 3.355 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  18.591 ms/op
                 getUser·p0.9999: 20.495 ms/op
                 getUser·p1.00:   21.430 ms/op

Iteration   2: 3.236 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.525 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   6.619 ms/op
                 getUser·p0.999:  20.153 ms/op
                 getUser·p0.9999: 28.385 ms/op
                 getUser·p1.00:   33.391 ms/op

Iteration   3: 3.281 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   4.049 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  16.562 ms/op
                 getUser·p0.9999: 27.221 ms/op
                 getUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291603
  mean =      3.290 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13964 
    [ 2.500,  5.000) = 267308 
    [ 5.000,  7.500) = 9013 
    [ 7.500, 10.000) = 750 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     17.885 ms/op
     p(99.9900) =     27.275 ms/op
     p(99.9990) =     29.532 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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
# Warmup Iteration   1: 10.411 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.010 ms/op
Iteration   1: 3.890 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  16.231 ms/op
                 listUser·p0.9999: 21.307 ms/op
                 listUser·p1.00:   22.938 ms/op

Iteration   2: 3.941 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.684 ms/op
                 listUser·p0.99:   8.321 ms/op
                 listUser·p0.999:  14.465 ms/op
                 listUser·p0.9999: 31.945 ms/op
                 listUser·p1.00:   33.686 ms/op

Iteration   3: 3.859 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.802 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  12.861 ms/op
                 listUser·p0.9999: 15.890 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246341
  mean =      3.896 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 196 
    [ 2.500,  5.000) = 237133 
    [ 5.000,  7.500) = 6265 
    [ 7.500, 10.000) = 1805 
    [10.000, 12.500) = 356 
    [12.500, 15.000) = 386 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.995 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     14.270 ms/op
     p(99.9900) =     24.555 ms/op
     p(99.9990) =     32.360 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.626 ± 1.688  ops/ms
ClientPb.existUser                       thrpt       3  10.102 ± 1.682  ops/ms
ClientPb.getUser                         thrpt       3   9.809 ± 2.189  ops/ms
ClientPb.listUser                        thrpt       3   8.323 ± 4.267  ops/ms
ClientPb.createUser                       avgt       3   3.311 ± 0.648   ms/op
ClientPb.existUser                        avgt       3   3.159 ± 0.400   ms/op
ClientPb.getUser                          avgt       3   3.262 ± 0.696   ms/op
ClientPb.listUser                         avgt       3   3.856 ± 0.436   ms/op
ClientPb.createUser                     sample  286804   3.349 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.279           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.157           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.365           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.039           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.107           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.142           ms/op
ClientPb.existUser                      sample  300905   3.189 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.951           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.482           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.785           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.275           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.927           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.443           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.560           ms/op
ClientPb.getUser                        sample  291603   3.290 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.631           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.586           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.885           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.275           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.391           ms/op
ClientPb.listUser                       sample  246341   3.896 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.995           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.760           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.270           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.555           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.686           ms/op
