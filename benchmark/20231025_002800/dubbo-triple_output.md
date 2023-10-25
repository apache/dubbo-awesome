# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.175 ops/ms
# Warmup Iteration   2: 2.763 ops/ms
# Warmup Iteration   3: 5.828 ops/ms
Iteration   1: 6.037 ops/ms
Iteration   2: 6.496 ops/ms
Iteration   3: 6.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.377 ±(99.9%) 5.459 ops/ms [Average]
  (min, avg, max) = (6.037, 6.377, 6.599), stdev = 0.299
  CI (99.9%): [0.918, 11.836] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:18
# Fork: 1 of 1
# Warmup Iteration   1: 1.983 ops/ms
# Warmup Iteration   2: 5.578 ops/ms
# Warmup Iteration   3: 6.445 ops/ms
Iteration   1: 6.435 ops/ms
Iteration   2: 6.621 ops/ms
Iteration   3: 6.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.603 ±(99.9%) 2.898 ops/ms [Average]
  (min, avg, max) = (6.435, 6.603, 6.751), stdev = 0.159
  CI (99.9%): [3.705, 9.501] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.896 ops/ms
# Warmup Iteration   2: 5.693 ops/ms
# Warmup Iteration   3: 6.543 ops/ms
Iteration   1: 6.243 ops/ms
Iteration   2: 5.316 ops/ms
Iteration   3: 5.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.827 ±(99.9%) 8.594 ops/ms [Average]
  (min, avg, max) = (5.316, 5.827, 6.243), stdev = 0.471
  CI (99.9%): [≈ 0, 14.421] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.654 ops/ms
# Warmup Iteration   2: 3.941 ops/ms
# Warmup Iteration   3: 4.689 ops/ms
Iteration   1: 5.268 ops/ms
Iteration   2: 5.285 ops/ms
Iteration   3: 5.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.261 ±(99.9%) 0.512 ops/ms [Average]
  (min, avg, max) = (5.230, 5.261, 5.285), stdev = 0.028
  CI (99.9%): [4.749, 5.773] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.716 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 5.254 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.090 ±(99.9%) 0.009 ms/op
Iteration   1: 5.033 ±(99.9%) 0.011 ms/op
Iteration   2: 5.717 ±(99.9%) 0.012 ms/op
Iteration   3: 5.792 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.514 ±(99.9%) 7.630 ms/op [Average]
  (min, avg, max) = (5.033, 5.514, 5.792), stdev = 0.418
  CI (99.9%): [≈ 0, 13.144] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 15.891 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.810 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.411 ±(99.9%) 0.008 ms/op
Iteration   1: 5.391 ±(99.9%) 0.011 ms/op
Iteration   2: 5.413 ±(99.9%) 0.008 ms/op
Iteration   3: 5.408 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.404 ±(99.9%) 0.204 ms/op [Average]
  (min, avg, max) = (5.391, 5.404, 5.413), stdev = 0.011
  CI (99.9%): [5.200, 5.608] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.350 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 5.921 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.155 ±(99.9%) 0.008 ms/op
Iteration   1: 5.062 ±(99.9%) 0.009 ms/op
Iteration   2: 5.092 ±(99.9%) 0.012 ms/op
Iteration   3: 5.019 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.058 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (5.019, 5.058, 5.092), stdev = 0.036
  CI (99.9%): [4.397, 5.719] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.143 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 8.629 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 7.457 ±(99.9%) 0.011 ms/op
Iteration   1: 7.283 ±(99.9%) 0.010 ms/op
Iteration   2: 7.209 ±(99.9%) 0.013 ms/op
Iteration   3: 7.260 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.251 ±(99.9%) 0.692 ms/op [Average]
  (min, avg, max) = (7.209, 7.251, 7.283), stdev = 0.038
  CI (99.9%): [6.559, 7.942] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 20.056 ±(99.9%) 0.342 ms/op
# Warmup Iteration   2: 6.885 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.672 ±(99.9%) 0.026 ms/op
Iteration   1: 5.813 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.236 ms/op
                 createUser·p0.50:   5.472 ms/op
                 createUser·p0.90:   7.586 ms/op
                 createUser·p0.95:   8.946 ms/op
                 createUser·p0.99:   13.792 ms/op
                 createUser·p0.999:  26.378 ms/op
                 createUser·p0.9999: 28.622 ms/op
                 createUser·p1.00:   29.819 ms/op

Iteration   2: 6.038 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.884 ms/op
                 createUser·p0.50:   5.693 ms/op
                 createUser·p0.90:   7.438 ms/op
                 createUser·p0.95:   8.913 ms/op
                 createUser·p0.99:   12.747 ms/op
                 createUser·p0.999:  17.531 ms/op
                 createUser·p0.9999: 31.844 ms/op
                 createUser·p1.00:   33.948 ms/op

Iteration   3: 5.283 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.796 ms/op
                 createUser·p0.50:   4.932 ms/op
                 createUser·p0.90:   6.873 ms/op
                 createUser·p0.95:   8.004 ms/op
                 createUser·p0.99:   11.207 ms/op
                 createUser·p0.999:  26.051 ms/op
                 createUser·p0.9999: 34.140 ms/op
                 createUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168603
  mean =      5.693 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 91 
    [ 2.500,  5.000) = 57006 
    [ 5.000,  7.500) = 96585 
    [ 7.500, 10.000) = 10442 
    [10.000, 12.500) = 2691 
    [12.500, 15.000) = 1043 
    [15.000, 17.500) = 441 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.796 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.299 ms/op
     p(95.0000) =      8.585 ms/op
     p(99.0000) =     12.665 ms/op
     p(99.9000) =     23.095 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     35.174 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.277 ±(99.9%) 0.247 ms/op
# Warmup Iteration   2: 7.253 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 4.777 ±(99.9%) 0.018 ms/op
Iteration   1: 4.972 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.073 ms/op
                 existUser·p0.50:   4.751 ms/op
                 existUser·p0.90:   6.259 ms/op
                 existUser·p0.95:   7.414 ms/op
                 existUser·p0.99:   9.945 ms/op
                 existUser·p0.999:  19.293 ms/op
                 existUser·p0.9999: 27.848 ms/op
                 existUser·p1.00:   28.803 ms/op

Iteration   2: 5.802 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.066 ms/op
                 existUser·p0.50:   5.505 ms/op
                 existUser·p0.90:   7.012 ms/op
                 existUser·p0.95:   8.315 ms/op
                 existUser·p0.99:   12.190 ms/op
                 existUser·p0.999:  20.312 ms/op
                 existUser·p0.9999: 29.293 ms/op
                 existUser·p1.00:   29.491 ms/op

Iteration   3: 5.504 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   1.907 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   7.168 ms/op
                 existUser·p0.95:   8.454 ms/op
                 existUser·p0.99:   12.714 ms/op
                 existUser·p0.999:  27.611 ms/op
                 existUser·p0.9999: 46.117 ms/op
                 existUser·p1.00:   49.283 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177644
  mean =      5.404 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 78558 
    [ 5.000, 10.000) = 95515 
    [10.000, 15.000) = 2921 
    [15.000, 20.000) = 425 
    [20.000, 25.000) = 93 
    [25.000, 30.000) = 98 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.907 ms/op
     p(50.0000) =      5.128 ms/op
     p(90.0000) =      6.857 ms/op
     p(95.0000) =      7.979 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     22.053 ms/op
     p(99.9900) =     39.584 ms/op
     p(99.9990) =     49.029 ms/op
     p(99.9999) =     49.283 ms/op
    p(100.0000) =     49.283 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.216 ±(99.9%) 0.252 ms/op
# Warmup Iteration   2: 5.435 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.997 ±(99.9%) 0.019 ms/op
Iteration   1: 5.047 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.913 ms/op
                 getUser·p0.50:   4.702 ms/op
                 getUser·p0.90:   6.463 ms/op
                 getUser·p0.95:   7.471 ms/op
                 getUser·p0.99:   10.903 ms/op
                 getUser·p0.999:  22.030 ms/op
                 getUser·p0.9999: 32.407 ms/op
                 getUser·p1.00:   32.866 ms/op

Iteration   2: 5.153 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.183 ms/op
                 getUser·p0.50:   4.751 ms/op
                 getUser·p0.90:   6.922 ms/op
                 getUser·p0.95:   8.045 ms/op
                 getUser·p0.99:   11.066 ms/op
                 getUser·p0.999:  21.490 ms/op
                 getUser·p0.9999: 26.201 ms/op
                 getUser·p1.00:   26.870 ms/op

Iteration   3: 4.866 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   4.645 ms/op
                 getUser·p0.90:   5.938 ms/op
                 getUser·p0.95:   6.668 ms/op
                 getUser·p0.99:   9.241 ms/op
                 getUser·p0.999:  15.756 ms/op
                 getUser·p0.9999: 30.671 ms/op
                 getUser·p1.00:   31.064 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 191217
  mean =      5.019 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 121043 
    [ 5.000,  7.500) = 60923 
    [ 7.500, 10.000) = 6815 
    [10.000, 12.500) = 1538 
    [12.500, 15.000) = 471 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      4.694 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.463 ms/op
     p(99.0000) =     10.502 ms/op
     p(99.9000) =     21.882 ms/op
     p(99.9900) =     30.851 ms/op
     p(99.9990) =     32.807 ms/op
     p(99.9999) =     32.866 ms/op
    p(100.0000) =     32.866 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 16.104 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 6.567 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.616 ±(99.9%) 0.023 ms/op
Iteration   1: 5.918 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.079 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.266 ms/op
                 listUser·p0.99:   10.759 ms/op
                 listUser·p0.999:  26.901 ms/op
                 listUser·p0.9999: 34.824 ms/op
                 listUser·p1.00:   36.504 ms/op

Iteration   2: 6.934 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.088 ms/op
                 listUser·p0.50:   6.562 ms/op
                 listUser·p0.90:   8.258 ms/op
                 listUser·p0.95:   9.585 ms/op
                 listUser·p0.99:   14.025 ms/op
                 listUser·p0.999:  29.574 ms/op
                 listUser·p0.9999: 33.973 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   3: 6.707 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.052 ms/op
                 listUser·p0.50:   6.308 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   9.994 ms/op
                 listUser·p0.99:   13.795 ms/op
                 listUser·p0.999:  25.723 ms/op
                 listUser·p0.9999: 27.573 ms/op
                 listUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147892
  mean =      6.490 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 13431 
    [ 5.000,  7.500) = 113923 
    [ 7.500, 10.000) = 15386 
    [10.000, 12.500) = 3390 
    [12.500, 15.000) = 904 
    [15.000, 17.500) = 308 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.079 ms/op
     p(50.0000) =      6.218 ms/op
     p(90.0000) =      7.963 ms/op
     p(95.0000) =      9.273 ms/op
     p(99.0000) =     12.861 ms/op
     p(99.9000) =     26.509 ms/op
     p(99.9900) =     33.686 ms/op
     p(99.9990) =     36.064 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.377 ± 5.459  ops/ms
ClientPb.existUser                       thrpt       3   6.603 ± 2.898  ops/ms
ClientPb.getUser                         thrpt       3   5.827 ± 8.594  ops/ms
ClientPb.listUser                        thrpt       3   5.261 ± 0.512  ops/ms
ClientPb.createUser                       avgt       3   5.514 ± 7.630   ms/op
ClientPb.existUser                        avgt       3   5.404 ± 0.204   ms/op
ClientPb.getUser                          avgt       3   5.058 ± 0.661   ms/op
ClientPb.listUser                         avgt       3   7.251 ± 0.692   ms/op
ClientPb.createUser                     sample  168603   5.693 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.796           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.299           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.585           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.665           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.095           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.882           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.848           ms/op
ClientPb.existUser                      sample  177644   5.404 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.907           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.857           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.979           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.600           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.053           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.584           ms/op
ClientPb.existUser:existUser·p1.00      sample          49.283           ms/op
ClientPb.getUser                        sample  191217   5.019 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.708           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.694           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.406           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.463           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.502           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.882           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.851           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.866           ms/op
ClientPb.listUser                       sample  147892   6.490 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.079           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.218           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.963           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.273           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.861           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.509           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.686           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.504           ms/op
