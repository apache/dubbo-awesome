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
# Warmup Iteration   1: 1.035 ops/ms
# Warmup Iteration   2: 2.241 ops/ms
# Warmup Iteration   3: 4.775 ops/ms
Iteration   1: 5.485 ops/ms
Iteration   2: 5.535 ops/ms
Iteration   3: 5.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.518 ±(99.9%) 0.528 ops/ms [Average]
  (min, avg, max) = (5.485, 5.518, 5.535), stdev = 0.029
  CI (99.9%): [4.990, 6.047] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.444 ops/ms
# Warmup Iteration   2: 4.454 ops/ms
# Warmup Iteration   3: 5.425 ops/ms
Iteration   1: 6.091 ops/ms
Iteration   2: 5.809 ops/ms
Iteration   3: 6.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.011 ±(99.9%) 3.208 ops/ms [Average]
  (min, avg, max) = (5.809, 6.011, 6.132), stdev = 0.176
  CI (99.9%): [2.802, 9.219] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.619 ops/ms
# Warmup Iteration   2: 4.317 ops/ms
# Warmup Iteration   3: 5.551 ops/ms
Iteration   1: 5.584 ops/ms
Iteration   2: 5.617 ops/ms
Iteration   3: 5.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.646 ±(99.9%) 1.459 ops/ms [Average]
  (min, avg, max) = (5.584, 5.646, 5.736), stdev = 0.080
  CI (99.9%): [4.186, 7.105] (assumes normal distribution)


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
# Warmup Iteration   1: 1.492 ops/ms
# Warmup Iteration   2: 3.768 ops/ms
# Warmup Iteration   3: 4.618 ops/ms
Iteration   1: 4.836 ops/ms
Iteration   2: 4.793 ops/ms
Iteration   3: 4.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.778 ±(99.9%) 1.191 ops/ms [Average]
  (min, avg, max) = (4.707, 4.778, 4.836), stdev = 0.065
  CI (99.9%): [3.588, 5.969] (assumes normal distribution)


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
# Warmup Iteration   1: 19.830 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 6.694 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.527 ±(99.9%) 0.011 ms/op
Iteration   1: 5.622 ±(99.9%) 0.009 ms/op
Iteration   2: 5.521 ±(99.9%) 0.012 ms/op
Iteration   3: 5.537 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.560 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (5.521, 5.560, 5.622), stdev = 0.054
  CI (99.9%): [4.569, 6.550] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 18.096 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 7.202 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.575 ±(99.9%) 0.010 ms/op
Iteration   1: 5.284 ±(99.9%) 0.009 ms/op
Iteration   2: 5.292 ±(99.9%) 0.009 ms/op
Iteration   3: 5.399 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.325 ±(99.9%) 1.173 ms/op [Average]
  (min, avg, max) = (5.284, 5.325, 5.399), stdev = 0.064
  CI (99.9%): [4.152, 6.498] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 17.801 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 6.627 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.860 ±(99.9%) 0.011 ms/op
Iteration   1: 5.711 ±(99.9%) 0.007 ms/op
Iteration   2: 5.848 ±(99.9%) 0.009 ms/op
Iteration   3: 5.715 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.758 ±(99.9%) 1.418 ms/op [Average]
  (min, avg, max) = (5.711, 5.758, 5.848), stdev = 0.078
  CI (99.9%): [4.340, 7.176] (assumes normal distribution)


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
# Warmup Iteration   1: 19.700 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 8.244 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 7.014 ±(99.9%) 0.014 ms/op
Iteration   1: 6.833 ±(99.9%) 0.011 ms/op
Iteration   2: 6.857 ±(99.9%) 0.012 ms/op
Iteration   3: 6.798 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.829 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (6.798, 6.829, 6.857), stdev = 0.030
  CI (99.9%): [6.287, 7.371] (assumes normal distribution)


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
# Warmup Iteration   1: 19.442 ±(99.9%) 0.372 ms/op
# Warmup Iteration   2: 7.978 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 6.186 ±(99.9%) 0.030 ms/op
Iteration   1: 6.277 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.413 ms/op
                 createUser·p0.50:   5.874 ms/op
                 createUser·p0.90:   8.192 ms/op
                 createUser·p0.95:   9.388 ms/op
                 createUser·p0.99:   12.894 ms/op
                 createUser·p0.999:  26.118 ms/op
                 createUser·p0.9999: 54.127 ms/op
                 createUser·p1.00:   63.177 ms/op

Iteration   2: 5.957 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.335 ms/op
                 createUser·p0.50:   5.571 ms/op
                 createUser·p0.90:   7.643 ms/op
                 createUser·p0.95:   8.765 ms/op
                 createUser·p0.99:   11.829 ms/op
                 createUser·p0.999:  27.208 ms/op
                 createUser·p0.9999: 31.740 ms/op
                 createUser·p1.00:   33.554 ms/op

Iteration   3: 5.867 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.075 ms/op
                 createUser·p0.50:   5.538 ms/op
                 createUser·p0.90:   7.283 ms/op
                 createUser·p0.95:   8.249 ms/op
                 createUser·p0.99:   11.698 ms/op
                 createUser·p0.999:  27.558 ms/op
                 createUser·p0.9999: 31.723 ms/op
                 createUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 159190
  mean =      6.028 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 35594 
    [ 5.000, 10.000) = 119334 
    [10.000, 15.000) = 3689 
    [15.000, 20.000) = 323 
    [20.000, 25.000) = 59 
    [25.000, 30.000) = 108 
    [30.000, 35.000) = 51 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 16 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 7 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      5.644 ms/op
     p(90.0000) =      7.700 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     12.190 ms/op
     p(99.9000) =     27.087 ms/op
     p(99.9900) =     46.376 ms/op
     p(99.9990) =     63.022 ms/op
     p(99.9999) =     63.177 ms/op
    p(100.0000) =     63.177 ms/op


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
# Warmup Iteration   1: 18.214 ±(99.9%) 0.291 ms/op
# Warmup Iteration   2: 6.578 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.801 ±(99.9%) 0.023 ms/op
Iteration   1: 5.571 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.355 ms/op
                 existUser·p0.50:   5.128 ms/op
                 existUser·p0.90:   7.332 ms/op
                 existUser·p0.95:   8.667 ms/op
                 existUser·p0.99:   12.042 ms/op
                 existUser·p0.999:  18.958 ms/op
                 existUser·p0.9999: 27.141 ms/op
                 existUser·p1.00:   27.754 ms/op

Iteration   2: 5.561 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.281 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   6.930 ms/op
                 existUser·p0.95:   8.454 ms/op
                 existUser·p0.99:   12.386 ms/op
                 existUser·p0.999:  27.624 ms/op
                 existUser·p0.9999: 36.766 ms/op
                 existUser·p1.00:   37.487 ms/op

Iteration   3: 5.470 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.939 ms/op
                 existUser·p0.95:   8.421 ms/op
                 existUser·p0.99:   11.510 ms/op
                 existUser·p0.999:  28.697 ms/op
                 existUser·p0.9999: 33.323 ms/op
                 existUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 173405
  mean =      5.533 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36 
    [ 2.500,  5.000) = 74768 
    [ 5.000,  7.500) = 84500 
    [ 7.500, 10.000) = 10160 
    [10.000, 12.500) = 2538 
    [12.500, 15.000) = 847 
    [15.000, 17.500) = 306 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.358 ms/op
     p(50.0000) =      5.120 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.531 ms/op
     p(99.0000) =     12.009 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     32.833 ms/op
     p(99.9990) =     37.150 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


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
# Warmup Iteration   1: 19.201 ±(99.9%) 0.360 ms/op
# Warmup Iteration   2: 7.599 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.263 ±(99.9%) 0.030 ms/op
Iteration   1: 6.070 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   5.595 ms/op
                 getUser·p0.90:   8.069 ms/op
                 getUser·p0.95:   9.175 ms/op
                 getUser·p0.99:   12.861 ms/op
                 getUser·p0.999:  19.355 ms/op
                 getUser·p0.9999: 29.137 ms/op
                 getUser·p1.00:   29.655 ms/op

Iteration   2: 6.224 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   2.929 ms/op
                 getUser·p0.50:   5.628 ms/op
                 getUser·p0.90:   8.585 ms/op
                 getUser·p0.95:   9.961 ms/op
                 getUser·p0.99:   13.269 ms/op
                 getUser·p0.999:  29.524 ms/op
                 getUser·p0.9999: 36.561 ms/op
                 getUser·p1.00:   36.831 ms/op

Iteration   3: 5.726 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.952 ms/op
                 getUser·p0.50:   5.456 ms/op
                 getUser·p0.90:   6.898 ms/op
                 getUser·p0.95:   7.963 ms/op
                 getUser·p0.99:   11.272 ms/op
                 getUser·p0.999:  28.977 ms/op
                 getUser·p0.9999: 34.171 ms/op
                 getUser·p1.00:   38.601 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 159983
  mean =      5.999 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 37994 
    [ 5.000,  7.500) = 102139 
    [ 7.500, 10.000) = 14648 
    [10.000, 12.500) = 3560 
    [12.500, 15.000) = 1070 
    [15.000, 17.500) = 278 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 22 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.640 ms/op
     p(50.0000) =      5.546 ms/op
     p(90.0000) =      7.905 ms/op
     p(95.0000) =      9.142 ms/op
     p(99.0000) =     12.534 ms/op
     p(99.9000) =     25.234 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     37.539 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


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
# Warmup Iteration   1: 19.739 ±(99.9%) 0.341 ms/op
# Warmup Iteration   2: 8.380 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 7.109 ±(99.9%) 0.035 ms/op
Iteration   1: 7.011 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   6.537 ms/op
                 listUser·p0.90:   8.847 ms/op
                 listUser·p0.95:   10.420 ms/op
                 listUser·p0.99:   14.139 ms/op
                 listUser·p0.999:  30.323 ms/op
                 listUser·p0.9999: 35.198 ms/op
                 listUser·p1.00:   36.438 ms/op

Iteration   2: 6.729 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   3.232 ms/op
                 listUser·p0.50:   6.308 ms/op
                 listUser·p0.90:   8.323 ms/op
                 listUser·p0.95:   9.552 ms/op
                 listUser·p0.99:   12.976 ms/op
                 listUser·p0.999:  31.897 ms/op
                 listUser·p0.9999: 35.127 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   3: 6.929 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   6.513 ms/op
                 listUser·p0.90:   8.847 ms/op
                 listUser·p0.95:   9.994 ms/op
                 listUser·p0.99:   13.029 ms/op
                 listUser·p0.999:  30.201 ms/op
                 listUser·p0.9999: 36.332 ms/op
                 listUser·p1.00:   37.421 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 139301
  mean =      6.887 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 3191 
    [ 5.000,  7.500) = 106630 
    [ 7.500, 10.000) = 22576 
    [10.000, 12.500) = 4731 
    [12.500, 15.000) = 1427 
    [15.000, 17.500) = 314 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 101 
    [32.500, 35.000) = 59 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      2.257 ms/op
     p(50.0000) =      6.447 ms/op
     p(90.0000) =      8.684 ms/op
     p(95.0000) =      9.978 ms/op
     p(99.0000) =     13.304 ms/op
     p(99.9000) =     30.966 ms/op
     p(99.9900) =     35.918 ms/op
     p(99.9990) =     37.318 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.518 ± 0.528  ops/ms
ClientPb.existUser                       thrpt       3   6.011 ± 3.208  ops/ms
ClientPb.getUser                         thrpt       3   5.646 ± 1.459  ops/ms
ClientPb.listUser                        thrpt       3   4.778 ± 1.191  ops/ms
ClientPb.createUser                       avgt       3   5.560 ± 0.990   ms/op
ClientPb.existUser                        avgt       3   5.325 ± 1.173   ms/op
ClientPb.getUser                          avgt       3   5.758 ± 1.418   ms/op
ClientPb.listUser                         avgt       3   6.829 ± 0.542   ms/op
ClientPb.createUser                     sample  159190   6.028 ± 0.015   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.413           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.644           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.700           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.847           ms/op
ClientPb.createUser:createUser·p0.99    sample          12.190           ms/op
ClientPb.createUser:createUser·p0.999   sample          27.087           ms/op
ClientPb.createUser:createUser·p0.9999  sample          46.376           ms/op
ClientPb.createUser:createUser·p1.00    sample          63.177           ms/op
ClientPb.existUser                      sample  173405   5.533 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.358           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.120           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.062           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.531           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.009           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.890           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.833           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.487           ms/op
ClientPb.getUser                        sample  159983   5.999 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.640           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.546           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.905           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.142           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.534           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.234           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.144           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.601           ms/op
ClientPb.listUser                       sample  139301   6.887 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.257           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.447           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.684           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.978           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.304           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.966           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.918           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.421           ms/op
