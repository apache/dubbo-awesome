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
# Warmup Iteration   1: 1.829 ops/ms
# Warmup Iteration   2: 4.913 ops/ms
# Warmup Iteration   3: 8.499 ops/ms
Iteration   1: 8.613 ops/ms
Iteration   2: 9.196 ops/ms
Iteration   3: 8.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.906 ±(99.9%) 5.315 ops/ms [Average]
  (min, avg, max) = (8.613, 8.906, 9.196), stdev = 0.291
  CI (99.9%): [3.591, 14.222] (assumes normal distribution)


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
# Warmup Iteration   1: 2.623 ops/ms
# Warmup Iteration   2: 8.643 ops/ms
# Warmup Iteration   3: 9.354 ops/ms
Iteration   1: 9.505 ops/ms
Iteration   2: 9.542 ops/ms
Iteration   3: 9.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.448 ±(99.9%) 2.427 ops/ms [Average]
  (min, avg, max) = (9.296, 9.448, 9.542), stdev = 0.133
  CI (99.9%): [7.021, 11.875] (assumes normal distribution)


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
# Warmup Iteration   1: 2.413 ops/ms
# Warmup Iteration   2: 8.049 ops/ms
# Warmup Iteration   3: 8.908 ops/ms
Iteration   1: 9.208 ops/ms
Iteration   2: 8.908 ops/ms
Iteration   3: 9.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.065 ±(99.9%) 2.751 ops/ms [Average]
  (min, avg, max) = (8.908, 9.065, 9.208), stdev = 0.151
  CI (99.9%): [6.314, 11.815] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.365 ops/ms
# Warmup Iteration   2: 6.863 ops/ms
# Warmup Iteration   3: 7.563 ops/ms
Iteration   1: 7.494 ops/ms
Iteration   2: 7.572 ops/ms
Iteration   3: 7.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.521 ±(99.9%) 0.810 ops/ms [Average]
  (min, avg, max) = (7.494, 7.521, 7.572), stdev = 0.044
  CI (99.9%): [6.711, 8.330] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.789 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.805 ±(99.9%) 0.005 ms/op
Iteration   1: 3.462 ±(99.9%) 0.009 ms/op
Iteration   2: 3.533 ±(99.9%) 0.005 ms/op
Iteration   3: 3.552 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.516 ±(99.9%) 0.866 ms/op [Average]
  (min, avg, max) = (3.462, 3.516, 3.552), stdev = 0.047
  CI (99.9%): [2.650, 4.382] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.490 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.368 ±(99.9%) 0.004 ms/op
Iteration   1: 3.354 ±(99.9%) 0.007 ms/op
Iteration   2: 3.435 ±(99.9%) 0.004 ms/op
Iteration   3: 3.400 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.396 ±(99.9%) 0.743 ms/op [Average]
  (min, avg, max) = (3.354, 3.396, 3.435), stdev = 0.041
  CI (99.9%): [2.653, 4.140] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.847 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.472 ±(99.9%) 0.004 ms/op
Iteration   1: 3.522 ±(99.9%) 0.005 ms/op
Iteration   2: 3.452 ±(99.9%) 0.006 ms/op
Iteration   3: 3.460 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.478 ±(99.9%) 0.702 ms/op [Average]
  (min, avg, max) = (3.452, 3.478, 3.522), stdev = 0.038
  CI (99.9%): [2.776, 4.180] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.225 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.628 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.255 ±(99.9%) 0.007 ms/op
Iteration   1: 4.216 ±(99.9%) 0.008 ms/op
Iteration   2: 4.228 ±(99.9%) 0.005 ms/op
Iteration   3: 4.257 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.234 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (4.216, 4.234, 4.257), stdev = 0.021
  CI (99.9%): [3.852, 4.616] (assumes normal distribution)


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
# Warmup Iteration   1: 10.745 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.014 ms/op
Iteration   1: 3.432 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   6.406 ms/op
                 createUser·p0.999:  22.056 ms/op
                 createUser·p0.9999: 29.275 ms/op
                 createUser·p1.00:   30.310 ms/op

Iteration   2: 3.652 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   7.016 ms/op
                 createUser·p0.999:  23.655 ms/op
                 createUser·p0.9999: 68.682 ms/op
                 createUser·p1.00:   69.730 ms/op

Iteration   3: 3.528 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.294 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   7.217 ms/op
                 createUser·p0.999:  22.643 ms/op
                 createUser·p0.9999: 29.976 ms/op
                 createUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271412
  mean =      3.535 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 263624 
    [ 5.000, 10.000) = 6941 
    [10.000, 15.000) = 447 
    [15.000, 20.000) = 54 
    [20.000, 25.000) = 206 
    [25.000, 30.000) = 96 
    [30.000, 35.000) = 12 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     22.708 ms/op
     p(99.9900) =     67.006 ms/op
     p(99.9990) =     69.375 ms/op
     p(99.9999) =     69.730 ms/op
    p(100.0000) =     69.730 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.420 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.618 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.010 ms/op
Iteration   1: 3.411 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  21.692 ms/op
                 existUser·p0.9999: 24.528 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   2: 3.439 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.785 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   7.397 ms/op
                 existUser·p0.999:  22.184 ms/op
                 existUser·p0.9999: 27.329 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   3: 3.426 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.194 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.988 ms/op
                 existUser·p0.999:  15.743 ms/op
                 existUser·p0.9999: 29.742 ms/op
                 existUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280031
  mean =      3.425 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5815 
    [ 2.500,  5.000) = 264705 
    [ 5.000,  7.500) = 7458 
    [ 7.500, 10.000) = 1250 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     18.120 ms/op
     p(99.9900) =     28.410 ms/op
     p(99.9990) =     31.759 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.265 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.016 ms/op
Iteration   1: 3.603 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   7.750 ms/op
                 getUser·p0.999:  21.234 ms/op
                 getUser·p0.9999: 23.695 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 3.489 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.300 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  23.170 ms/op
                 getUser·p0.9999: 26.214 ms/op
                 getUser·p1.00:   27.656 ms/op

Iteration   3: 3.484 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   7.087 ms/op
                 getUser·p0.999:  12.750 ms/op
                 getUser·p0.9999: 29.721 ms/op
                 getUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272284
  mean =      3.525 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2828 
    [ 2.500,  5.000) = 259632 
    [ 5.000,  7.500) = 7759 
    [ 7.500, 10.000) = 1391 
    [10.000, 12.500) = 322 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.914 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     16.014 ms/op
     p(99.9900) =     29.189 ms/op
     p(99.9990) =     30.622 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 11.363 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.569 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.290 ±(99.9%) 0.016 ms/op
Iteration   1: 4.296 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.159 ms/op
                 listUser·p0.50:   4.162 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  23.358 ms/op
                 listUser·p0.9999: 26.953 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   2: 4.262 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  16.268 ms/op
                 listUser·p0.9999: 18.743 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   3: 4.190 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.915 ms/op
                 listUser·p0.50:   4.047 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  16.329 ms/op
                 listUser·p0.9999: 18.767 ms/op
                 listUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 225979
  mean =      4.249 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 137 
    [ 2.500,  5.000) = 213986 
    [ 5.000,  7.500) = 8061 
    [ 7.500, 10.000) = 2788 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 385 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      1.159 ms/op
     p(50.0000) =      4.100 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      8.421 ms/op
     p(99.9000) =     16.646 ms/op
     p(99.9900) =     25.500 ms/op
     p(99.9990) =     27.349 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.906 ± 5.315  ops/ms
ClientPb.existUser                       thrpt       3   9.448 ± 2.427  ops/ms
ClientPb.getUser                         thrpt       3   9.065 ± 2.751  ops/ms
ClientPb.listUser                        thrpt       3   7.521 ± 0.810  ops/ms
ClientPb.createUser                       avgt       3   3.516 ± 0.866   ms/op
ClientPb.existUser                        avgt       3   3.396 ± 0.743   ms/op
ClientPb.getUser                          avgt       3   3.478 ± 0.702   ms/op
ClientPb.listUser                         avgt       3   4.234 ± 0.382   ms/op
ClientPb.createUser                     sample  271412   3.535 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.839           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.400           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.914           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.708           ms/op
ClientPb.createUser:createUser·p0.9999  sample          67.006           ms/op
ClientPb.createUser:createUser·p1.00    sample          69.730           ms/op
ClientPb.existUser                      sample  280031   3.425 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.098           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.062           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.120           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.410           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.014           ms/op
ClientPb.getUser                        sample  272284   3.525 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.161           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.351           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.914           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.209           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.014           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.189           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.999           ms/op
ClientPb.listUser                       sample  225979   4.249 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.159           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.063           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.421           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.646           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.500           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.525           ms/op
