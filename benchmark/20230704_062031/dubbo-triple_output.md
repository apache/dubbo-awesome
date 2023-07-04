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
# Warmup Iteration   1: 0.980 ops/ms
# Warmup Iteration   2: 2.302 ops/ms
# Warmup Iteration   3: 4.945 ops/ms
Iteration   1: 5.690 ops/ms
Iteration   2: 5.831 ops/ms
Iteration   3: 5.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.810 ±(99.9%) 2.036 ops/ms [Average]
  (min, avg, max) = (5.690, 5.810, 5.910), stdev = 0.112
  CI (99.9%): [3.774, 7.846] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.797 ops/ms
# Warmup Iteration   2: 5.297 ops/ms
# Warmup Iteration   3: 6.080 ops/ms
Iteration   1: 6.299 ops/ms
Iteration   2: 6.612 ops/ms
Iteration   3: 6.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.493 ±(99.9%) 3.090 ops/ms [Average]
  (min, avg, max) = (6.299, 6.493, 6.612), stdev = 0.169
  CI (99.9%): [3.403, 9.583] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.641 ops/ms
# Warmup Iteration   2: 4.752 ops/ms
# Warmup Iteration   3: 5.876 ops/ms
Iteration   1: 5.595 ops/ms
Iteration   2: 5.775 ops/ms
Iteration   3: 5.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.711 ±(99.9%) 1.833 ops/ms [Average]
  (min, avg, max) = (5.595, 5.711, 5.775), stdev = 0.100
  CI (99.9%): [3.878, 7.544] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.610 ops/ms
# Warmup Iteration   2: 4.078 ops/ms
# Warmup Iteration   3: 4.791 ops/ms
Iteration   1: 5.151 ops/ms
Iteration   2: 4.913 ops/ms
Iteration   3: 4.928 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.997 ±(99.9%) 2.431 ops/ms [Average]
  (min, avg, max) = (4.913, 4.997, 5.151), stdev = 0.133
  CI (99.9%): [2.566, 7.429] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 18.554 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 6.509 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.953 ±(99.9%) 0.019 ms/op
Iteration   1: 5.609 ±(99.9%) 0.011 ms/op
Iteration   2: 5.494 ±(99.9%) 0.013 ms/op
Iteration   3: 5.388 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.497 ±(99.9%) 2.014 ms/op [Average]
  (min, avg, max) = (5.388, 5.497, 5.609), stdev = 0.110
  CI (99.9%): [3.483, 7.511] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 17.899 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 6.280 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.506 ±(99.9%) 0.011 ms/op
Iteration   1: 5.193 ±(99.9%) 0.013 ms/op
Iteration   2: 5.347 ±(99.9%) 0.012 ms/op
Iteration   3: 5.231 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.257 ±(99.9%) 1.463 ms/op [Average]
  (min, avg, max) = (5.193, 5.257, 5.347), stdev = 0.080
  CI (99.9%): [3.793, 6.720] (assumes normal distribution)


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
# Warmup Iteration   1: 16.049 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 7.305 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.591 ±(99.9%) 0.014 ms/op
Iteration   1: 5.787 ±(99.9%) 0.014 ms/op
Iteration   2: 5.737 ±(99.9%) 0.013 ms/op
Iteration   3: 5.701 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.742 ±(99.9%) 0.783 ms/op [Average]
  (min, avg, max) = (5.701, 5.742, 5.787), stdev = 0.043
  CI (99.9%): [4.959, 6.525] (assumes normal distribution)


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
# Warmup Iteration   1: 18.502 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 7.696 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.250 ±(99.9%) 0.015 ms/op
Iteration   1: 6.642 ±(99.9%) 0.018 ms/op
Iteration   2: 6.616 ±(99.9%) 0.009 ms/op
Iteration   3: 6.281 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.513 ±(99.9%) 3.676 ms/op [Average]
  (min, avg, max) = (6.281, 6.513, 6.642), stdev = 0.202
  CI (99.9%): [2.837, 10.189] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.806 ±(99.9%) 0.287 ms/op
# Warmup Iteration   2: 6.750 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.909 ±(99.9%) 0.025 ms/op
Iteration   1: 5.533 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.367 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.726 ms/op
                 createUser·p0.95:   8.151 ms/op
                 createUser·p0.99:   10.977 ms/op
                 createUser·p0.999:  23.120 ms/op
                 createUser·p0.9999: 29.997 ms/op
                 createUser·p1.00:   32.178 ms/op

Iteration   2: 5.735 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.499 ms/op
                 createUser·p0.50:   5.489 ms/op
                 createUser·p0.90:   6.947 ms/op
                 createUser·p0.95:   7.782 ms/op
                 createUser·p0.99:   10.896 ms/op
                 createUser·p0.999:  25.690 ms/op
                 createUser·p0.9999: 30.069 ms/op
                 createUser·p1.00:   30.999 ms/op

Iteration   3: 5.740 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.609 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   7.037 ms/op
                 createUser·p0.95:   8.217 ms/op
                 createUser·p0.99:   12.222 ms/op
                 createUser·p0.999:  21.698 ms/op
                 createUser·p0.9999: 32.577 ms/op
                 createUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169287
  mean =      5.668 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 47420 
    [ 5.000,  7.500) = 110735 
    [ 7.500, 10.000) = 8113 
    [10.000, 12.500) = 1924 
    [12.500, 15.000) = 629 
    [15.000, 17.500) = 168 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.367 ms/op
     p(50.0000) =      5.382 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      8.020 ms/op
     p(99.0000) =     11.452 ms/op
     p(99.9000) =     23.396 ms/op
     p(99.9900) =     30.935 ms/op
     p(99.9990) =     33.312 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.034 ±(99.9%) 0.289 ms/op
# Warmup Iteration   2: 6.281 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.439 ±(99.9%) 0.020 ms/op
Iteration   1: 5.371 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.294 ms/op
                 existUser·p0.50:   5.136 ms/op
                 existUser·p0.90:   6.447 ms/op
                 existUser·p0.95:   7.183 ms/op
                 existUser·p0.99:   9.732 ms/op
                 existUser·p0.999:  14.283 ms/op
                 existUser·p0.9999: 26.150 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   2: 5.480 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.095 ms/op
                 existUser·p0.50:   5.153 ms/op
                 existUser·p0.90:   6.617 ms/op
                 existUser·p0.95:   7.627 ms/op
                 existUser·p0.99:   10.995 ms/op
                 existUser·p0.999:  26.841 ms/op
                 existUser·p0.9999: 32.386 ms/op
                 existUser·p1.00:   33.063 ms/op

Iteration   3: 5.567 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.363 ms/op
                 existUser·p0.50:   5.300 ms/op
                 existUser·p0.90:   6.676 ms/op
                 existUser·p0.95:   7.512 ms/op
                 existUser·p0.99:   10.494 ms/op
                 existUser·p0.999:  28.774 ms/op
                 existUser·p0.9999: 33.818 ms/op
                 existUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175283
  mean =      5.472 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 66220 
    [ 5.000,  7.500) = 100711 
    [ 7.500, 10.000) = 6314 
    [10.000, 12.500) = 1299 
    [12.500, 15.000) = 346 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 56 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.095 ms/op
     p(50.0000) =      5.194 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      7.406 ms/op
     p(99.0000) =     10.338 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     33.078 ms/op
     p(99.9990) =     35.274 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


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
# Warmup Iteration   1: 20.275 ±(99.9%) 0.373 ms/op
# Warmup Iteration   2: 7.494 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 6.141 ±(99.9%) 0.024 ms/op
Iteration   1: 5.703 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.966 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   6.988 ms/op
                 getUser·p0.95:   8.364 ms/op
                 getUser·p0.99:   11.649 ms/op
                 getUser·p0.999:  25.326 ms/op
                 getUser·p0.9999: 28.166 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   2: 5.608 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.535 ms/op
                 getUser·p0.50:   5.341 ms/op
                 getUser·p0.90:   6.537 ms/op
                 getUser·p0.95:   7.537 ms/op
                 getUser·p0.99:   10.891 ms/op
                 getUser·p0.999:  26.508 ms/op
                 getUser·p0.9999: 29.392 ms/op
                 getUser·p1.00:   31.064 ms/op

Iteration   3: 5.864 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   5.620 ms/op
                 getUser·p0.90:   6.881 ms/op
                 getUser·p0.95:   7.995 ms/op
                 getUser·p0.99:   11.239 ms/op
                 getUser·p0.999:  28.447 ms/op
                 getUser·p0.9999: 35.622 ms/op
                 getUser·p1.00:   36.045 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167684
  mean =      5.723 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 37667 
    [ 5.000,  7.500) = 119349 
    [ 7.500, 10.000) = 7496 
    [10.000, 12.500) = 2145 
    [12.500, 15.000) = 554 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.726 ms/op
     p(50.0000) =      5.431 ms/op
     p(90.0000) =      6.799 ms/op
     p(95.0000) =      7.995 ms/op
     p(99.0000) =     11.321 ms/op
     p(99.9000) =     25.875 ms/op
     p(99.9900) =     33.406 ms/op
     p(99.9990) =     35.779 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 20.506 ±(99.9%) 0.339 ms/op
# Warmup Iteration   2: 7.784 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.554 ±(99.9%) 0.025 ms/op
Iteration   1: 6.742 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.621 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   7.938 ms/op
                 listUser·p0.95:   9.159 ms/op
                 listUser·p0.99:   12.485 ms/op
                 listUser·p0.999:  28.983 ms/op
                 listUser·p0.9999: 32.383 ms/op
                 listUser·p1.00:   32.997 ms/op

Iteration   2: 6.280 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.679 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   7.897 ms/op
                 listUser·p0.99:   11.190 ms/op
                 listUser·p0.999:  28.120 ms/op
                 listUser·p0.9999: 30.260 ms/op
                 listUser·p1.00:   31.195 ms/op

Iteration   3: 6.579 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.572 ms/op
                 listUser·p0.50:   6.341 ms/op
                 listUser·p0.90:   7.463 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   12.009 ms/op
                 listUser·p0.999:  22.839 ms/op
                 listUser·p0.9999: 30.857 ms/op
                 listUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147029
  mean =      6.528 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 3705 
    [ 5.000,  7.500) = 127605 
    [ 7.500, 10.000) = 11750 
    [10.000, 12.500) = 2808 
    [12.500, 15.000) = 669 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 120 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.572 ms/op
     p(50.0000) =      6.275 ms/op
     p(90.0000) =      7.569 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     11.928 ms/op
     p(99.9000) =     27.886 ms/op
     p(99.9900) =     31.270 ms/op
     p(99.9990) =     32.890 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.810 ± 2.036  ops/ms
ClientPb.existUser                       thrpt       3   6.493 ± 3.090  ops/ms
ClientPb.getUser                         thrpt       3   5.711 ± 1.833  ops/ms
ClientPb.listUser                        thrpt       3   4.997 ± 2.431  ops/ms
ClientPb.createUser                       avgt       3   5.497 ± 2.014   ms/op
ClientPb.existUser                        avgt       3   5.257 ± 1.463   ms/op
ClientPb.getUser                          avgt       3   5.742 ± 0.783   ms/op
ClientPb.listUser                         avgt       3   6.513 ± 3.676   ms/op
ClientPb.createUser                     sample  169287   5.668 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.367           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.922           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.020           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.452           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.396           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.935           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.948           ms/op
ClientPb.existUser                      sample  175283   5.472 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.095           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.194           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.578           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.406           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.338           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.120           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.078           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.521           ms/op
ClientPb.getUser                        sample  167684   5.723 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.726           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.431           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.799           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.995           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.321           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.875           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.406           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.045           ms/op
ClientPb.listUser                       sample  147029   6.528 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.572           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.275           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.928           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.886           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.270           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.997           ms/op
