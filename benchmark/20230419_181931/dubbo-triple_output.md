# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.966 ops/ms
# Warmup Iteration   2: 2.136 ops/ms
# Warmup Iteration   3: 4.307 ops/ms
Iteration   1: 4.795 ops/ms
Iteration   2: 4.977 ops/ms
Iteration   3: 5.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.986 ±(99.9%) 3.559 ops/ms [Average]
  (min, avg, max) = (4.795, 4.986, 5.185), stdev = 0.195
  CI (99.9%): [1.427, 8.545] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.306 ops/ms
# Warmup Iteration   2: 4.282 ops/ms
# Warmup Iteration   3: 5.247 ops/ms
Iteration   1: 5.335 ops/ms
Iteration   2: 5.438 ops/ms
Iteration   3: 5.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.417 ±(99.9%) 1.346 ops/ms [Average]
  (min, avg, max) = (5.335, 5.417, 5.478), stdev = 0.074
  CI (99.9%): [4.071, 6.763] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.322 ops/ms
# Warmup Iteration   2: 3.972 ops/ms
# Warmup Iteration   3: 4.998 ops/ms
Iteration   1: 5.246 ops/ms
Iteration   2: 5.609 ops/ms
Iteration   3: 5.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.337 ±(99.9%) 4.393 ops/ms [Average]
  (min, avg, max) = (5.154, 5.337, 5.609), stdev = 0.241
  CI (99.9%): [0.944, 9.729] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.383 ops/ms
# Warmup Iteration   2: 3.658 ops/ms
# Warmup Iteration   3: 4.257 ops/ms
Iteration   1: 4.168 ops/ms
Iteration   2: 4.496 ops/ms
Iteration   3: 4.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.382 ±(99.9%) 3.374 ops/ms [Average]
  (min, avg, max) = (4.168, 4.382, 4.496), stdev = 0.185
  CI (99.9%): [1.008, 7.756] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 22.264 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 8.058 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 6.525 ±(99.9%) 0.009 ms/op
Iteration   1: 6.560 ±(99.9%) 0.011 ms/op
Iteration   2: 6.151 ±(99.9%) 0.008 ms/op
Iteration   3: 6.276 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.329 ±(99.9%) 3.819 ms/op [Average]
  (min, avg, max) = (6.151, 6.329, 6.560), stdev = 0.209
  CI (99.9%): [2.510, 10.148] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 19.772 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 7.474 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.058 ±(99.9%) 0.015 ms/op
Iteration   1: 6.136 ±(99.9%) 0.008 ms/op
Iteration   2: 5.873 ±(99.9%) 0.011 ms/op
Iteration   3: 5.960 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.990 ±(99.9%) 2.446 ms/op [Average]
  (min, avg, max) = (5.873, 5.990, 6.136), stdev = 0.134
  CI (99.9%): [3.544, 8.436] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 20.036 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 8.841 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.533 ±(99.9%) 0.019 ms/op
Iteration   1: 6.113 ±(99.9%) 0.011 ms/op
Iteration   2: 6.394 ±(99.9%) 0.009 ms/op
Iteration   3: 5.973 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.160 ±(99.9%) 3.904 ms/op [Average]
  (min, avg, max) = (5.973, 6.160, 6.394), stdev = 0.214
  CI (99.9%): [2.256, 10.064] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 22.043 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 8.679 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 7.090 ±(99.9%) 0.012 ms/op
Iteration   1: 7.202 ±(99.9%) 0.011 ms/op
Iteration   2: 7.888 ±(99.9%) 0.019 ms/op
Iteration   3: 6.895 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.328 ±(99.9%) 9.273 ms/op [Average]
  (min, avg, max) = (6.895, 7.328, 7.888), stdev = 0.508
  CI (99.9%): [≈ 0, 16.601] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 20.102 ±(99.9%) 0.320 ms/op
# Warmup Iteration   2: 7.871 ±(99.9%) 0.058 ms/op
# Warmup Iteration   3: 6.794 ±(99.9%) 0.035 ms/op
Iteration   1: 6.252 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.703 ms/op
                 createUser·p0.50:   5.997 ms/op
                 createUser·p0.90:   7.668 ms/op
                 createUser·p0.95:   8.536 ms/op
                 createUser·p0.99:   11.092 ms/op
                 createUser·p0.999:  30.394 ms/op
                 createUser·p0.9999: 36.234 ms/op
                 createUser·p1.00:   37.093 ms/op

Iteration   2: 6.092 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.658 ms/op
                 createUser·p0.50:   5.841 ms/op
                 createUser·p0.90:   7.479 ms/op
                 createUser·p0.95:   8.233 ms/op
                 createUser·p0.99:   10.781 ms/op
                 createUser·p0.999:  32.682 ms/op
                 createUser·p0.9999: 35.389 ms/op
                 createUser·p1.00:   36.438 ms/op

Iteration   3: 6.141 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.278 ms/op
                 createUser·p0.50:   5.833 ms/op
                 createUser·p0.90:   7.586 ms/op
                 createUser·p0.95:   8.618 ms/op
                 createUser·p0.99:   12.206 ms/op
                 createUser·p0.999:  18.448 ms/op
                 createUser·p0.9999: 31.149 ms/op
                 createUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 155756
  mean =      6.161 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 21325 
    [ 5.000,  7.500) = 117749 
    [ 7.500, 10.000) = 13488 
    [10.000, 12.500) = 2391 
    [12.500, 15.000) = 436 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 79 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      5.890 ms/op
     p(90.0000) =      7.578 ms/op
     p(95.0000) =      8.487 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     28.687 ms/op
     p(99.9900) =     34.669 ms/op
     p(99.9990) =     36.947 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.437 ±(99.9%) 0.314 ms/op
# Warmup Iteration   2: 7.034 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 6.003 ±(99.9%) 0.022 ms/op
Iteration   1: 5.979 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.580 ms/op
                 existUser·p0.50:   5.734 ms/op
                 existUser·p0.90:   7.258 ms/op
                 existUser·p0.95:   8.421 ms/op
                 existUser·p0.99:   10.748 ms/op
                 existUser·p0.999:  27.329 ms/op
                 existUser·p0.9999: 37.005 ms/op
                 existUser·p1.00:   38.142 ms/op

Iteration   2: 5.838 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   5.530 ms/op
                 existUser·p0.90:   7.225 ms/op
                 existUser·p0.95:   8.315 ms/op
                 existUser·p0.99:   11.567 ms/op
                 existUser·p0.999:  16.433 ms/op
                 existUser·p0.9999: 30.954 ms/op
                 existUser·p1.00:   31.982 ms/op

Iteration   3: 6.133 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   2.724 ms/op
                 existUser·p0.50:   5.784 ms/op
                 existUser·p0.90:   7.651 ms/op
                 existUser·p0.95:   8.864 ms/op
                 existUser·p0.99:   12.780 ms/op
                 existUser·p0.999:  18.481 ms/op
                 existUser·p0.9999: 30.991 ms/op
                 existUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 160434
  mean =      5.981 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 32337 
    [ 5.000,  7.500) = 113206 
    [ 7.500, 10.000) = 11136 
    [10.000, 12.500) = 2599 
    [12.500, 15.000) = 709 
    [15.000, 17.500) = 272 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      5.652 ms/op
     p(90.0000) =      7.397 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     11.731 ms/op
     p(99.9000) =     18.012 ms/op
     p(99.9900) =     36.039 ms/op
     p(99.9990) =     37.508 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.377 ±(99.9%) 0.340 ms/op
# Warmup Iteration   2: 8.640 ±(99.9%) 0.067 ms/op
# Warmup Iteration   3: 6.365 ±(99.9%) 0.024 ms/op
Iteration   1: 6.144 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.597 ms/op
                 getUser·p0.50:   5.775 ms/op
                 getUser·p0.90:   7.602 ms/op
                 getUser·p0.95:   8.831 ms/op
                 getUser·p0.99:   12.452 ms/op
                 getUser·p0.999:  25.264 ms/op
                 getUser·p0.9999: 27.584 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   2: 6.380 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.941 ms/op
                 getUser·p0.50:   5.939 ms/op
                 getUser·p0.90:   7.987 ms/op
                 getUser·p0.95:   9.437 ms/op
                 getUser·p0.99:   13.595 ms/op
                 getUser·p0.999:  28.996 ms/op
                 getUser·p0.9999: 34.597 ms/op
                 getUser·p1.00:   35.521 ms/op

Iteration   3: 6.238 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.397 ms/op
                 getUser·p0.50:   5.997 ms/op
                 getUser·p0.90:   7.651 ms/op
                 getUser·p0.95:   8.831 ms/op
                 getUser·p0.99:   11.616 ms/op
                 getUser·p0.999:  15.932 ms/op
                 getUser·p0.9999: 28.721 ms/op
                 getUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 153448
  mean =      6.252 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 18527 
    [ 5.000,  7.500) = 116453 
    [ 7.500, 10.000) = 13722 
    [10.000, 12.500) = 3231 
    [12.500, 15.000) = 996 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      5.898 ms/op
     p(90.0000) =      7.750 ms/op
     p(95.0000) =      9.044 ms/op
     p(99.0000) =     12.452 ms/op
     p(99.9000) =     25.217 ms/op
     p(99.9900) =     31.959 ms/op
     p(99.9990) =     35.485 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 21.458 ±(99.9%) 0.390 ms/op
# Warmup Iteration   2: 8.728 ±(99.9%) 0.062 ms/op
# Warmup Iteration   3: 7.268 ±(99.9%) 0.033 ms/op
Iteration   1: 7.221 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   6.824 ms/op
                 listUser·p0.90:   8.962 ms/op
                 listUser·p0.95:   10.207 ms/op
                 listUser·p0.99:   13.713 ms/op
                 listUser·p0.999:  28.388 ms/op
                 listUser·p0.9999: 30.722 ms/op
                 listUser·p1.00:   31.392 ms/op

Iteration   2: 7.514 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   7.184 ms/op
                 listUser·p0.90:   9.273 ms/op
                 listUser·p0.95:   10.502 ms/op
                 listUser·p0.99:   14.549 ms/op
                 listUser·p0.999:  31.671 ms/op
                 listUser·p0.9999: 38.813 ms/op
                 listUser·p1.00:   39.715 ms/op

Iteration   3: 7.413 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   3.682 ms/op
                 listUser·p0.50:   7.037 ms/op
                 listUser·p0.90:   9.241 ms/op
                 listUser·p0.95:   10.551 ms/op
                 listUser·p0.99:   13.550 ms/op
                 listUser·p0.999:  32.309 ms/op
                 listUser·p0.9999: 41.005 ms/op
                 listUser·p1.00:   41.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 130014
  mean =      7.381 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 1154 
    [ 5.000, 10.000) = 120432 
    [10.000, 15.000) = 7574 
    [15.000, 20.000) = 466 
    [20.000, 25.000) = 91 
    [25.000, 30.000) = 133 
    [30.000, 35.000) = 119 
    [35.000, 40.000) = 40 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.154 ms/op
     p(50.0000) =      7.004 ms/op
     p(90.0000) =      9.159 ms/op
     p(95.0000) =     10.437 ms/op
     p(99.0000) =     14.008 ms/op
     p(99.9000) =     30.704 ms/op
     p(99.9900) =     38.403 ms/op
     p(99.9990) =     41.091 ms/op
     p(99.9999) =     41.091 ms/op
    p(100.0000) =     41.091 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   4.986 ± 3.559  ops/ms
ClientPb.existUser                       thrpt       3   5.417 ± 1.346  ops/ms
ClientPb.getUser                         thrpt       3   5.337 ± 4.393  ops/ms
ClientPb.listUser                        thrpt       3   4.382 ± 3.374  ops/ms
ClientPb.createUser                       avgt       3   6.329 ± 3.819   ms/op
ClientPb.existUser                        avgt       3   5.990 ± 2.446   ms/op
ClientPb.getUser                          avgt       3   6.160 ± 3.904   ms/op
ClientPb.listUser                         avgt       3   7.328 ± 9.273   ms/op
ClientPb.createUser                     sample  155756   6.161 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.278           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.890           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.578           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.487           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.370           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.687           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.669           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.093           ms/op
ClientPb.existUser                      sample  160434   5.981 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.253           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.652           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.397           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.503           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.731           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.012           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.039           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.142           ms/op
ClientPb.getUser                        sample  153448   6.252 ± 0.014   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.397           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.898           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.750           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.044           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.452           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.217           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.959           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.521           ms/op
ClientPb.listUser                       sample  130014   7.381 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.154           ms/op
ClientPb.listUser:listUser·p0.50        sample           7.004           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.159           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.437           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.008           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.704           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.403           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.091           ms/op
