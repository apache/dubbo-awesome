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
# Warmup Iteration   1: 2.041 ops/ms
# Warmup Iteration   2: 5.672 ops/ms
# Warmup Iteration   3: 8.390 ops/ms
Iteration   1: 9.013 ops/ms
Iteration   2: 9.255 ops/ms
Iteration   3: 9.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.134 ±(99.9%) 2.200 ops/ms [Average]
  (min, avg, max) = (9.013, 9.134, 9.255), stdev = 0.121
  CI (99.9%): [6.935, 11.334] (assumes normal distribution)


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
# Warmup Iteration   1: 2.765 ops/ms
# Warmup Iteration   2: 8.446 ops/ms
# Warmup Iteration   3: 9.182 ops/ms
Iteration   1: 9.795 ops/ms
Iteration   2: 9.306 ops/ms
Iteration   3: 9.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.555 ±(99.9%) 4.459 ops/ms [Average]
  (min, avg, max) = (9.306, 9.555, 9.795), stdev = 0.244
  CI (99.9%): [5.096, 14.013] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.769 ops/ms
# Warmup Iteration   2: 8.767 ops/ms
# Warmup Iteration   3: 8.867 ops/ms
Iteration   1: 9.087 ops/ms
Iteration   2: 9.278 ops/ms
Iteration   3: 9.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.250 ±(99.9%) 2.761 ops/ms [Average]
  (min, avg, max) = (9.087, 9.250, 9.386), stdev = 0.151
  CI (99.9%): [6.489, 12.012] (assumes normal distribution)


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
# Warmup Iteration   1: 2.727 ops/ms
# Warmup Iteration   2: 6.559 ops/ms
# Warmup Iteration   3: 7.610 ops/ms
Iteration   1: 7.613 ops/ms
Iteration   2: 7.714 ops/ms
Iteration   3: 7.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.701 ±(99.9%) 1.496 ops/ms [Average]
  (min, avg, max) = (7.613, 7.701, 7.776), stdev = 0.082
  CI (99.9%): [6.204, 9.197] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.524 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.667 ±(99.9%) 0.008 ms/op
Iteration   1: 3.482 ±(99.9%) 0.008 ms/op
Iteration   2: 3.667 ±(99.9%) 0.005 ms/op
Iteration   3: 3.628 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.592 ±(99.9%) 1.779 ms/op [Average]
  (min, avg, max) = (3.482, 3.592, 3.667), stdev = 0.098
  CI (99.9%): [1.814, 5.371] (assumes normal distribution)


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
# Warmup Iteration   1: 8.849 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.006 ms/op
Iteration   1: 3.424 ±(99.9%) 0.006 ms/op
Iteration   2: 3.391 ±(99.9%) 0.007 ms/op
Iteration   3: 3.292 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.369 ±(99.9%) 1.255 ms/op [Average]
  (min, avg, max) = (3.292, 3.369, 3.424), stdev = 0.069
  CI (99.9%): [2.114, 4.623] (assumes normal distribution)


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
# Warmup Iteration   1: 10.857 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.005 ms/op
Iteration   1: 3.541 ±(99.9%) 0.004 ms/op
Iteration   2: 3.498 ±(99.9%) 0.006 ms/op
Iteration   3: 3.519 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.519 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (3.498, 3.519, 3.541), stdev = 0.022
  CI (99.9%): [3.123, 3.916] (assumes normal distribution)


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
# Warmup Iteration   1: 12.226 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.453 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.004 ms/op
Iteration   1: 4.214 ±(99.9%) 0.007 ms/op
Iteration   2: 4.137 ±(99.9%) 0.011 ms/op
Iteration   3: 4.125 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.158 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (4.125, 4.158, 4.214), stdev = 0.048
  CI (99.9%): [3.275, 5.042] (assumes normal distribution)


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
# Warmup Iteration   1: 11.088 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.107 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.823 ±(99.9%) 0.013 ms/op
Iteration   1: 3.622 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   9.208 ms/op
                 createUser·p0.999:  17.260 ms/op
                 createUser·p0.9999: 20.644 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   2: 3.515 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   7.234 ms/op
                 createUser·p0.999:  17.990 ms/op
                 createUser·p0.9999: 20.543 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   3: 3.470 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.495 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   7.250 ms/op
                 createUser·p0.999:  19.952 ms/op
                 createUser·p0.9999: 29.707 ms/op
                 createUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271284
  mean =      3.535 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9863 
    [ 2.500,  5.000) = 251979 
    [ 5.000,  7.500) = 6531 
    [ 7.500, 10.000) = 1900 
    [10.000, 12.500) = 477 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 179 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.620 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     23.568 ms/op
     p(99.9990) =     30.919 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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
# Warmup Iteration   1: 8.179 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.627 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.010 ms/op
Iteration   1: 3.482 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.583 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  20.513 ms/op
                 existUser·p0.9999: 23.390 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   2: 3.375 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.573 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.076 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  21.962 ms/op
                 existUser·p0.9999: 24.840 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 3.406 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.161 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   7.209 ms/op
                 existUser·p0.999:  15.574 ms/op
                 existUser·p0.9999: 28.770 ms/op
                 existUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280454
  mean =      3.420 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9774 
    [ 2.500,  5.000) = 262410 
    [ 5.000,  7.500) = 6461 
    [ 7.500, 10.000) = 1120 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     17.200 ms/op
     p(99.9900) =     28.049 ms/op
     p(99.9990) =     29.144 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 10.757 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.870 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.012 ms/op
Iteration   1: 3.490 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  19.148 ms/op
                 getUser·p0.9999: 24.549 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   2: 3.506 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.224 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  20.644 ms/op
                 getUser·p0.9999: 32.585 ms/op
                 getUser·p1.00:   34.800 ms/op

Iteration   3: 3.514 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   7.127 ms/op
                 getUser·p0.999:  19.530 ms/op
                 getUser·p0.9999: 26.305 ms/op
                 getUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273908
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5421 
    [ 2.500,  5.000) = 260263 
    [ 5.000,  7.500) = 6139 
    [ 7.500, 10.000) = 1388 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     31.150 ms/op
     p(99.9990) =     33.606 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


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
# Warmup Iteration   1: 11.709 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.500 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.273 ±(99.9%) 0.014 ms/op
Iteration   1: 4.230 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.780 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  22.249 ms/op
                 listUser·p0.9999: 26.134 ms/op
                 listUser·p1.00:   27.623 ms/op

Iteration   2: 4.135 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.942 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  15.557 ms/op
                 listUser·p0.9999: 17.048 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 4.163 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  14.959 ms/op
                 listUser·p0.9999: 22.086 ms/op
                 listUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229846
  mean =      4.175 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 85 
    [ 2.500,  5.000) = 218801 
    [ 5.000,  7.500) = 7155 
    [ 7.500, 10.000) = 2839 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 199 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.780 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      8.323 ms/op
     p(99.9000) =     16.613 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     26.614 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.134 ± 2.200  ops/ms
ClientPb.existUser                       thrpt       3   9.555 ± 4.459  ops/ms
ClientPb.getUser                         thrpt       3   9.250 ± 2.761  ops/ms
ClientPb.listUser                        thrpt       3   7.701 ± 1.496  ops/ms
ClientPb.createUser                       avgt       3   3.592 ± 1.779   ms/op
ClientPb.existUser                        avgt       3   3.369 ± 1.255   ms/op
ClientPb.getUser                          avgt       3   3.519 ± 0.396   ms/op
ClientPb.listUser                         avgt       3   4.158 ± 0.884   ms/op
ClientPb.createUser                     sample  271284   3.535 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.021           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.514           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.620           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.022           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.568           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.097           ms/op
ClientPb.existUser                      sample  280454   3.420 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.161           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.200           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.049           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.393           ms/op
ClientPb.getUser                        sample  273908   3.503 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.870           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.143           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.562           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.150           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.800           ms/op
ClientPb.listUser                       sample  229846   4.175 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.780           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.018           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.323           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.613           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.428           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.623           ms/op
