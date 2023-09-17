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
# Warmup Iteration   1: 1.887 ops/ms
# Warmup Iteration   2: 5.348 ops/ms
# Warmup Iteration   3: 8.223 ops/ms
Iteration   1: 8.785 ops/ms
Iteration   2: 8.730 ops/ms
Iteration   3: 8.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.722 ±(99.9%) 1.218 ops/ms [Average]
  (min, avg, max) = (8.652, 8.722, 8.785), stdev = 0.067
  CI (99.9%): [7.505, 9.940] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.800 ops/ms
# Warmup Iteration   2: 8.241 ops/ms
# Warmup Iteration   3: 8.612 ops/ms
Iteration   1: 9.265 ops/ms
Iteration   2: 9.074 ops/ms
Iteration   3: 9.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.229 ±(99.9%) 2.560 ops/ms [Average]
  (min, avg, max) = (9.074, 9.229, 9.348), stdev = 0.140
  CI (99.9%): [6.669, 11.789] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.587 ops/ms
# Warmup Iteration   2: 7.793 ops/ms
# Warmup Iteration   3: 8.901 ops/ms
Iteration   1: 8.646 ops/ms
Iteration   2: 8.745 ops/ms
Iteration   3: 8.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.679 ±(99.9%) 1.042 ops/ms [Average]
  (min, avg, max) = (8.646, 8.679, 8.745), stdev = 0.057
  CI (99.9%): [7.638, 9.721] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.288 ops/ms
# Warmup Iteration   2: 6.521 ops/ms
# Warmup Iteration   3: 7.427 ops/ms
Iteration   1: 7.788 ops/ms
Iteration   2: 7.746 ops/ms
Iteration   3: 7.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.628 ±(99.9%) 4.421 ops/ms [Average]
  (min, avg, max) = (7.349, 7.628, 7.788), stdev = 0.242
  CI (99.9%): [3.207, 12.049] (assumes normal distribution)


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
# Warmup Iteration   1: 10.970 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.004 ms/op
Iteration   1: 3.739 ±(99.9%) 0.003 ms/op
Iteration   2: 3.502 ±(99.9%) 0.003 ms/op
Iteration   3: 3.600 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.614 ±(99.9%) 2.172 ms/op [Average]
  (min, avg, max) = (3.502, 3.614, 3.739), stdev = 0.119
  CI (99.9%): [1.441, 5.786] (assumes normal distribution)


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
# Warmup Iteration   1: 9.232 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.860 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.004 ms/op
Iteration   1: 3.530 ±(99.9%) 0.004 ms/op
Iteration   2: 3.421 ±(99.9%) 0.006 ms/op
Iteration   3: 3.325 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.425 ±(99.9%) 1.875 ms/op [Average]
  (min, avg, max) = (3.325, 3.425, 3.530), stdev = 0.103
  CI (99.9%): [1.550, 5.301] (assumes normal distribution)


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
# Warmup Iteration   1: 9.775 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.729 ±(99.9%) 0.004 ms/op
Iteration   1: 3.579 ±(99.9%) 0.006 ms/op
Iteration   2: 3.764 ±(99.9%) 0.003 ms/op
Iteration   3: 3.532 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.625 ±(99.9%) 2.239 ms/op [Average]
  (min, avg, max) = (3.532, 3.625, 3.764), stdev = 0.123
  CI (99.9%): [1.386, 5.864] (assumes normal distribution)


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
# Warmup Iteration   1: 14.437 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 5.086 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.374 ±(99.9%) 0.009 ms/op
Iteration   1: 4.431 ±(99.9%) 0.011 ms/op
Iteration   2: 4.259 ±(99.9%) 0.008 ms/op
Iteration   3: 4.188 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.293 ±(99.9%) 2.281 ms/op [Average]
  (min, avg, max) = (4.188, 4.293, 4.431), stdev = 0.125
  CI (99.9%): [2.011, 6.574] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.548 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.015 ms/op
Iteration   1: 3.696 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.663 ms/op
                 createUser·p0.50:   3.502 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   5.095 ms/op
                 createUser·p0.99:   7.209 ms/op
                 createUser·p0.999:  21.135 ms/op
                 createUser·p0.9999: 25.297 ms/op
                 createUser·p1.00:   27.230 ms/op

Iteration   2: 3.544 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   3.453 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.562 ms/op
                 createUser·p0.999:  24.519 ms/op
                 createUser·p0.9999: 26.739 ms/op
                 createUser·p1.00:   27.492 ms/op

Iteration   3: 3.660 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.389 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  25.482 ms/op
                 createUser·p0.9999: 31.847 ms/op
                 createUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 264388
  mean =      3.632 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4116 
    [ 2.500,  5.000) = 251128 
    [ 5.000,  7.500) = 7200 
    [ 7.500, 10.000) = 1204 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 158 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     22.892 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     33.295 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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
# Warmup Iteration   1: 9.796 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.010 ms/op
Iteration   1: 3.450 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.841 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.181 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  19.115 ms/op
                 existUser·p0.9999: 20.930 ms/op
                 existUser·p1.00:   21.987 ms/op

Iteration   2: 3.473 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.679 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   6.523 ms/op
                 existUser·p0.999:  19.825 ms/op
                 existUser·p0.9999: 25.297 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 3.420 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.538 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   6.341 ms/op
                 existUser·p0.999:  13.377 ms/op
                 existUser·p0.9999: 26.575 ms/op
                 existUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 278454
  mean =      3.447 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6162 
    [ 2.500,  5.000) = 266001 
    [ 5.000,  7.500) = 4797 
    [ 7.500, 10.000) = 780 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     15.848 ms/op
     p(99.9900) =     25.897 ms/op
     p(99.9990) =     27.212 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 10.142 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.012 ms/op
Iteration   1: 3.856 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.712 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   6.095 ms/op
                 getUser·p0.99:   9.372 ms/op
                 getUser·p0.999:  24.419 ms/op
                 getUser·p0.9999: 35.043 ms/op
                 getUser·p1.00:   36.045 ms/op

Iteration   2: 3.600 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  12.394 ms/op
                 getUser·p0.9999: 25.443 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 3.709 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.729 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.293 ms/op
                 getUser·p0.95:   5.456 ms/op
                 getUser·p0.99:   7.922 ms/op
                 getUser·p0.999:  23.784 ms/op
                 getUser·p0.9999: 31.187 ms/op
                 getUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 257926
  mean =      3.719 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1234 
    [ 2.500,  5.000) = 242315 
    [ 5.000,  7.500) = 10569 
    [ 7.500, 10.000) = 2557 
    [10.000, 12.500) = 744 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.712 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      8.298 ms/op
     p(99.9000) =     23.305 ms/op
     p(99.9900) =     31.473 ms/op
     p(99.9990) =     36.045 ms/op
     p(99.9999) =     36.045 ms/op
    p(100.0000) =     36.045 ms/op


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
# Warmup Iteration   1: 12.471 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 4.933 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.388 ±(99.9%) 0.016 ms/op
Iteration   1: 4.323 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.704 ms/op
                 listUser·p0.99:   9.058 ms/op
                 listUser·p0.999:  22.875 ms/op
                 listUser·p0.9999: 29.262 ms/op
                 listUser·p1.00:   31.031 ms/op

Iteration   2: 4.370 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   4.211 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   8.569 ms/op
                 listUser·p0.999:  16.725 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 4.246 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 25.032 ms/op
                 listUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 222481
  mean =      4.312 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 204041 
    [ 5.000,  7.500) = 14695 
    [ 7.500, 10.000) = 2327 
    [10.000, 12.500) = 771 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.208 ms/op
     p(50.0000) =      4.088 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     25.715 ms/op
     p(99.9990) =     30.501 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.722 ± 1.218  ops/ms
ClientPb.existUser                       thrpt       3   9.229 ± 2.560  ops/ms
ClientPb.getUser                         thrpt       3   8.679 ± 1.042  ops/ms
ClientPb.listUser                        thrpt       3   7.628 ± 4.421  ops/ms
ClientPb.createUser                       avgt       3   3.614 ± 2.172   ms/op
ClientPb.existUser                        avgt       3   3.425 ± 1.875   ms/op
ClientPb.getUser                          avgt       3   3.625 ± 2.239   ms/op
ClientPb.listUser                         avgt       3   4.293 ± 2.281   ms/op
ClientPb.createUser                     sample  264388   3.632 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.083           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.473           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.053           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.892           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.853           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.423           ms/op
ClientPb.existUser                      sample  278454   3.447 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.841           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.351           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.137           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.414           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.848           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.897           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.329           ms/op
ClientPb.getUser                        sample  257926   3.719 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.712           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.478           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.267           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.298           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.305           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.473           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.045           ms/op
ClientPb.listUser                       sample  222481   4.312 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.208           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.505           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.612           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.715           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.031           ms/op
