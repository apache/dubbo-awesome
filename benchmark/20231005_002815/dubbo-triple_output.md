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
# Warmup Iteration   1: 1.132 ops/ms
# Warmup Iteration   2: 2.462 ops/ms
# Warmup Iteration   3: 5.148 ops/ms
Iteration   1: 5.328 ops/ms
Iteration   2: 5.514 ops/ms
Iteration   3: 5.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.508 ±(99.9%) 3.238 ops/ms [Average]
  (min, avg, max) = (5.328, 5.508, 5.683), stdev = 0.177
  CI (99.9%): [2.270, 8.746] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.658 ops/ms
# Warmup Iteration   2: 4.372 ops/ms
# Warmup Iteration   3: 5.893 ops/ms
Iteration   1: 5.923 ops/ms
Iteration   2: 5.871 ops/ms
Iteration   3: 5.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.919 ±(99.9%) 0.838 ops/ms [Average]
  (min, avg, max) = (5.871, 5.919, 5.962), stdev = 0.046
  CI (99.9%): [5.080, 6.757] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.662 ops/ms
# Warmup Iteration   2: 4.740 ops/ms
# Warmup Iteration   3: 5.552 ops/ms
Iteration   1: 5.587 ops/ms
Iteration   2: 5.648 ops/ms
Iteration   3: 5.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.695 ±(99.9%) 2.502 ops/ms [Average]
  (min, avg, max) = (5.587, 5.695, 5.849), stdev = 0.137
  CI (99.9%): [3.193, 8.196] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.647 ops/ms
# Warmup Iteration   2: 4.065 ops/ms
# Warmup Iteration   3: 5.009 ops/ms
Iteration   1: 4.793 ops/ms
Iteration   2: 4.944 ops/ms
Iteration   3: 4.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.871 ±(99.9%) 1.377 ops/ms [Average]
  (min, avg, max) = (4.793, 4.871, 4.944), stdev = 0.075
  CI (99.9%): [3.493, 6.248] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 19.486 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 7.127 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.333 ±(99.9%) 0.013 ms/op
Iteration   1: 5.796 ±(99.9%) 0.007 ms/op
Iteration   2: 5.861 ±(99.9%) 0.012 ms/op
Iteration   3: 5.798 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.818 ±(99.9%) 0.673 ms/op [Average]
  (min, avg, max) = (5.796, 5.818, 5.861), stdev = 0.037
  CI (99.9%): [5.146, 6.491] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 16.689 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 6.482 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.314 ±(99.9%) 0.012 ms/op
Iteration   1: 5.309 ±(99.9%) 0.012 ms/op
Iteration   2: 5.387 ±(99.9%) 0.007 ms/op
Iteration   3: 5.261 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.319 ±(99.9%) 1.156 ms/op [Average]
  (min, avg, max) = (5.261, 5.319, 5.387), stdev = 0.063
  CI (99.9%): [4.163, 6.475] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 18.504 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 7.578 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.029 ±(99.9%) 0.008 ms/op
Iteration   1: 5.648 ±(99.9%) 0.007 ms/op
Iteration   2: 5.769 ±(99.9%) 0.007 ms/op
Iteration   3: 5.613 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.677 ±(99.9%) 1.489 ms/op [Average]
  (min, avg, max) = (5.613, 5.677, 5.769), stdev = 0.082
  CI (99.9%): [4.187, 7.166] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 17.840 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 7.843 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.562 ±(99.9%) 0.013 ms/op
Iteration   1: 6.641 ±(99.9%) 0.011 ms/op
Iteration   2: 6.518 ±(99.9%) 0.012 ms/op
Iteration   3: 6.605 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.588 ±(99.9%) 1.154 ms/op [Average]
  (min, avg, max) = (6.518, 6.588, 6.641), stdev = 0.063
  CI (99.9%): [5.434, 7.742] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.069 ±(99.9%) 0.316 ms/op
# Warmup Iteration   2: 7.914 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 5.973 ±(99.9%) 0.030 ms/op
Iteration   1: 5.622 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   7.119 ms/op
                 createUser·p0.95:   8.020 ms/op
                 createUser·p0.99:   10.945 ms/op
                 createUser·p0.999:  26.182 ms/op
                 createUser·p0.9999: 31.500 ms/op
                 createUser·p1.00:   31.719 ms/op

Iteration   2: 5.613 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.601 ms/op
                 createUser·p0.50:   5.317 ms/op
                 createUser·p0.90:   6.939 ms/op
                 createUser·p0.95:   8.004 ms/op
                 createUser·p0.99:   11.960 ms/op
                 createUser·p0.999:  17.370 ms/op
                 createUser·p0.9999: 30.605 ms/op
                 createUser·p1.00:   31.457 ms/op

Iteration   3: 5.841 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.425 ms/op
                 createUser·p0.50:   5.423 ms/op
                 createUser·p0.90:   7.406 ms/op
                 createUser·p0.95:   8.700 ms/op
                 createUser·p0.99:   12.485 ms/op
                 createUser·p0.999:  31.864 ms/op
                 createUser·p0.9999: 38.089 ms/op
                 createUser·p1.00:   38.732 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168592
  mean =      5.690 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 52201 
    [ 5.000,  7.500) = 103272 
    [ 7.500, 10.000) = 9424 
    [10.000, 12.500) = 2487 
    [12.500, 15.000) = 683 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      7.160 ms/op
     p(95.0000) =      8.241 ms/op
     p(99.0000) =     11.698 ms/op
     p(99.9000) =     26.444 ms/op
     p(99.9900) =     35.455 ms/op
     p(99.9990) =     38.642 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.231 ±(99.9%) 0.288 ms/op
# Warmup Iteration   2: 6.082 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.446 ±(99.9%) 0.021 ms/op
Iteration   1: 5.720 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.445 ms/op
                 existUser·p0.50:   5.292 ms/op
                 existUser·p0.90:   7.422 ms/op
                 existUser·p0.95:   8.812 ms/op
                 existUser·p0.99:   12.337 ms/op
                 existUser·p0.999:  23.599 ms/op
                 existUser·p0.9999: 27.558 ms/op
                 existUser·p1.00:   27.951 ms/op

Iteration   2: 5.505 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.044 ms/op
                 existUser·p0.50:   5.177 ms/op
                 existUser·p0.90:   6.832 ms/op
                 existUser·p0.95:   8.102 ms/op
                 existUser·p0.99:   11.536 ms/op
                 existUser·p0.999:  17.331 ms/op
                 existUser·p0.9999: 31.850 ms/op
                 existUser·p1.00:   33.096 ms/op

Iteration   3: 5.687 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.322 ms/op
                 existUser·p0.50:   5.226 ms/op
                 existUser·p0.90:   7.569 ms/op
                 existUser·p0.95:   8.749 ms/op
                 existUser·p0.99:   11.256 ms/op
                 existUser·p0.999:  16.804 ms/op
                 existUser·p0.9999: 41.534 ms/op
                 existUser·p1.00:   42.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170202
  mean =      5.636 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 64172 
    [ 5.000, 10.000) = 102357 
    [10.000, 15.000) = 3272 
    [15.000, 20.000) = 273 
    [20.000, 25.000) = 28 
    [25.000, 30.000) = 39 
    [30.000, 35.000) = 35 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.044 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      7.307 ms/op
     p(95.0000) =      8.585 ms/op
     p(99.0000) =     11.649 ms/op
     p(99.9000) =     18.408 ms/op
     p(99.9900) =     39.316 ms/op
     p(99.9990) =     42.009 ms/op
     p(99.9999) =     42.009 ms/op
    p(100.0000) =     42.009 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.684 ±(99.9%) 0.325 ms/op
# Warmup Iteration   2: 7.244 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 5.961 ±(99.9%) 0.026 ms/op
Iteration   1: 5.766 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.890 ms/op
                 getUser·p0.50:   5.333 ms/op
                 getUser·p0.90:   7.406 ms/op
                 getUser·p0.95:   8.864 ms/op
                 getUser·p0.99:   12.091 ms/op
                 getUser·p0.999:  18.303 ms/op
                 getUser·p0.9999: 27.293 ms/op
                 getUser·p1.00:   30.409 ms/op

Iteration   2: 6.064 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   1.704 ms/op
                 getUser·p0.50:   5.571 ms/op
                 getUser·p0.90:   7.913 ms/op
                 getUser·p0.95:   9.568 ms/op
                 getUser·p0.99:   13.418 ms/op
                 getUser·p0.999:  28.508 ms/op
                 getUser·p0.9999: 33.252 ms/op
                 getUser·p1.00:   35.979 ms/op

Iteration   3: 5.816 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.347 ms/op
                 getUser·p0.50:   5.423 ms/op
                 getUser·p0.90:   7.438 ms/op
                 getUser·p0.95:   8.634 ms/op
                 getUser·p0.99:   11.764 ms/op
                 getUser·p0.999:  29.753 ms/op
                 getUser·p0.9999: 35.652 ms/op
                 getUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 163219
  mean =      5.880 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 43009 
    [ 5.000,  7.500) = 103301 
    [ 7.500, 10.000) = 11908 
    [10.000, 12.500) = 3357 
    [12.500, 15.000) = 992 
    [15.000, 17.500) = 236 
    [17.500, 20.000) = 178 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 60 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.704 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      7.578 ms/op
     p(95.0000) =      9.011 ms/op
     p(99.0000) =     12.485 ms/op
     p(99.9000) =     24.955 ms/op
     p(99.9900) =     33.753 ms/op
     p(99.9990) =     36.052 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 20.229 ±(99.9%) 0.398 ms/op
# Warmup Iteration   2: 8.314 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.816 ±(99.9%) 0.027 ms/op
Iteration   1: 6.858 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.597 ms/op
                 listUser·p0.50:   6.324 ms/op
                 listUser·p0.90:   8.847 ms/op
                 listUser·p0.95:   10.404 ms/op
                 listUser·p0.99:   14.385 ms/op
                 listUser·p0.999:  24.199 ms/op
                 listUser·p0.9999: 29.282 ms/op
                 listUser·p1.00:   32.047 ms/op

Iteration   2: 6.861 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   6.463 ms/op
                 listUser·p0.90:   8.634 ms/op
                 listUser·p0.95:   9.912 ms/op
                 listUser·p0.99:   13.009 ms/op
                 listUser·p0.999:  27.178 ms/op
                 listUser·p0.9999: 31.021 ms/op
                 listUser·p1.00:   32.309 ms/op

Iteration   3: 6.679 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   8.471 ms/op
                 listUser·p0.95:   9.961 ms/op
                 listUser·p0.99:   13.550 ms/op
                 listUser·p0.999:  26.051 ms/op
                 listUser·p0.9999: 28.840 ms/op
                 listUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141175
  mean =      6.798 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 4214 
    [ 5.000,  7.500) = 108227 
    [ 7.500, 10.000) = 21397 
    [10.000, 12.500) = 5073 
    [12.500, 15.000) = 1455 
    [15.000, 17.500) = 341 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 105 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.122 ms/op
     p(50.0000) =      6.316 ms/op
     p(90.0000) =      8.651 ms/op
     p(95.0000) =     10.076 ms/op
     p(99.0000) =     13.648 ms/op
     p(99.9000) =     25.821 ms/op
     p(99.9900) =     30.241 ms/op
     p(99.9990) =     32.282 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.508 ± 3.238  ops/ms
ClientPb.existUser                       thrpt       3   5.919 ± 0.838  ops/ms
ClientPb.getUser                         thrpt       3   5.695 ± 2.502  ops/ms
ClientPb.listUser                        thrpt       3   4.871 ± 1.377  ops/ms
ClientPb.createUser                       avgt       3   5.818 ± 0.673   ms/op
ClientPb.existUser                        avgt       3   5.319 ± 1.156   ms/op
ClientPb.getUser                          avgt       3   5.677 ± 1.489   ms/op
ClientPb.listUser                         avgt       3   6.588 ± 1.154   ms/op
ClientPb.createUser                     sample  168592   5.690 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.985           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.349           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.160           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.241           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.698           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.444           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.455           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.732           ms/op
ClientPb.existUser                      sample  170202   5.636 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.044           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.226           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.307           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.585           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.649           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.408           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.316           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.009           ms/op
ClientPb.getUser                        sample  163219   5.880 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.704           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.439           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.578           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.011           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.485           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.955           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.753           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.176           ms/op
ClientPb.listUser                       sample  141175   6.798 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.122           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.316           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.651           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.076           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.648           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.821           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.241           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.309           ms/op
