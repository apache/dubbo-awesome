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
# Warmup Iteration   1: 1.049 ops/ms
# Warmup Iteration   2: 2.214 ops/ms
# Warmup Iteration   3: 4.829 ops/ms
Iteration   1: 5.727 ops/ms
Iteration   2: 5.638 ops/ms
Iteration   3: 5.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.714 ±(99.9%) 1.285 ops/ms [Average]
  (min, avg, max) = (5.638, 5.714, 5.777), stdev = 0.070
  CI (99.9%): [4.430, 6.999] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.580 ops/ms
# Warmup Iteration   2: 4.499 ops/ms
# Warmup Iteration   3: 5.517 ops/ms
Iteration   1: 5.854 ops/ms
Iteration   2: 5.639 ops/ms
Iteration   3: 6.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.838 ±(99.9%) 3.487 ops/ms [Average]
  (min, avg, max) = (5.639, 5.838, 6.020), stdev = 0.191
  CI (99.9%): [2.351, 9.324] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.392 ops/ms
# Warmup Iteration   2: 4.071 ops/ms
# Warmup Iteration   3: 5.266 ops/ms
Iteration   1: 5.647 ops/ms
Iteration   2: 5.669 ops/ms
Iteration   3: 5.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.584 ±(99.9%) 2.335 ops/ms [Average]
  (min, avg, max) = (5.437, 5.584, 5.669), stdev = 0.128
  CI (99.9%): [3.250, 7.919] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.573 ops/ms
# Warmup Iteration   2: 3.600 ops/ms
# Warmup Iteration   3: 4.854 ops/ms
Iteration   1: 4.943 ops/ms
Iteration   2: 4.694 ops/ms
Iteration   3: 4.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.742 ±(99.9%) 3.311 ops/ms [Average]
  (min, avg, max) = (4.590, 4.742, 4.943), stdev = 0.181
  CI (99.9%): [1.432, 8.053] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 19.284 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.628 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.079 ±(99.9%) 0.013 ms/op
Iteration   1: 5.729 ±(99.9%) 0.011 ms/op
Iteration   2: 5.800 ±(99.9%) 0.008 ms/op
Iteration   3: 5.780 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.769 ±(99.9%) 0.669 ms/op [Average]
  (min, avg, max) = (5.729, 5.769, 5.800), stdev = 0.037
  CI (99.9%): [5.100, 6.439] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 16.726 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.223 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.856 ±(99.9%) 0.005 ms/op
Iteration   1: 5.519 ±(99.9%) 0.010 ms/op
Iteration   2: 5.761 ±(99.9%) 0.005 ms/op
Iteration   3: 5.448 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.576 ±(99.9%) 2.995 ms/op [Average]
  (min, avg, max) = (5.448, 5.576, 5.761), stdev = 0.164
  CI (99.9%): [2.582, 8.571] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.802 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 6.608 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 5.847 ±(99.9%) 0.013 ms/op
Iteration   1: 5.857 ±(99.9%) 0.009 ms/op
Iteration   2: 5.709 ±(99.9%) 0.013 ms/op
Iteration   3: 5.704 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.757 ±(99.9%) 1.582 ms/op [Average]
  (min, avg, max) = (5.704, 5.757, 5.857), stdev = 0.087
  CI (99.9%): [4.175, 7.338] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 19.822 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 8.099 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 7.001 ±(99.9%) 0.009 ms/op
Iteration   1: 6.883 ±(99.9%) 0.013 ms/op
Iteration   2: 6.597 ±(99.9%) 0.009 ms/op
Iteration   3: 6.764 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.748 ±(99.9%) 2.628 ms/op [Average]
  (min, avg, max) = (6.597, 6.748, 6.883), stdev = 0.144
  CI (99.9%): [4.120, 9.376] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.092 ±(99.9%) 0.318 ms/op
# Warmup Iteration   2: 6.639 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 6.479 ±(99.9%) 0.033 ms/op
Iteration   1: 5.680 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.066 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   7.193 ms/op
                 createUser·p0.95:   8.290 ms/op
                 createUser·p0.99:   10.469 ms/op
                 createUser·p0.999:  24.613 ms/op
                 createUser·p0.9999: 29.619 ms/op
                 createUser·p1.00:   30.835 ms/op

Iteration   2: 5.744 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.788 ms/op
                 createUser·p0.50:   5.538 ms/op
                 createUser·p0.90:   7.004 ms/op
                 createUser·p0.95:   7.619 ms/op
                 createUser·p0.99:   10.635 ms/op
                 createUser·p0.999:  15.909 ms/op
                 createUser·p0.9999: 34.013 ms/op
                 createUser·p1.00:   34.669 ms/op

Iteration   3: 5.534 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.552 ms/op
                 createUser·p0.50:   5.300 ms/op
                 createUser·p0.90:   6.693 ms/op
                 createUser·p0.95:   7.455 ms/op
                 createUser·p0.99:   10.438 ms/op
                 createUser·p0.999:  31.615 ms/op
                 createUser·p0.9999: 39.139 ms/op
                 createUser·p1.00:   39.322 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169836
  mean =      5.651 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 52953 
    [ 5.000,  7.500) = 106335 
    [ 7.500, 10.000) = 8398 
    [10.000, 12.500) = 1520 
    [12.500, 15.000) = 393 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.788 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.971 ms/op
     p(95.0000) =      7.807 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     18.061 ms/op
     p(99.9900) =     38.012 ms/op
     p(99.9990) =     39.322 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 15.941 ±(99.9%) 0.243 ms/op
# Warmup Iteration   2: 6.023 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.448 ±(99.9%) 0.021 ms/op
Iteration   1: 5.369 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.042 ms/op
                 existUser·p0.50:   5.095 ms/op
                 existUser·p0.90:   6.644 ms/op
                 existUser·p0.95:   7.406 ms/op
                 existUser·p0.99:   10.977 ms/op
                 existUser·p0.999:  23.559 ms/op
                 existUser·p0.9999: 27.920 ms/op
                 existUser·p1.00:   28.344 ms/op

Iteration   2: 5.435 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.138 ms/op
                 existUser·p0.50:   5.079 ms/op
                 existUser·p0.90:   6.988 ms/op
                 existUser·p0.95:   7.761 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  14.860 ms/op
                 existUser·p0.9999: 30.573 ms/op
                 existUser·p1.00:   31.359 ms/op

Iteration   3: 5.328 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.220 ms/op
                 existUser·p0.50:   5.087 ms/op
                 existUser·p0.90:   6.652 ms/op
                 existUser·p0.95:   7.438 ms/op
                 existUser·p0.99:   9.814 ms/op
                 existUser·p0.999:  31.064 ms/op
                 existUser·p0.9999: 34.275 ms/op
                 existUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 178394
  mean =      5.377 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 81054 
    [ 5.000,  7.500) = 88090 
    [ 7.500, 10.000) = 7011 
    [10.000, 12.500) = 1346 
    [12.500, 15.000) = 501 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 48 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.042 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.758 ms/op
     p(95.0000) =      7.537 ms/op
     p(99.0000) =     10.633 ms/op
     p(99.9000) =     20.107 ms/op
     p(99.9900) =     32.986 ms/op
     p(99.9990) =     34.870 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 16.773 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 6.157 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.836 ±(99.9%) 0.024 ms/op
Iteration   1: 5.638 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.789 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   7.406 ms/op
                 getUser·p0.95:   8.634 ms/op
                 getUser·p0.99:   12.927 ms/op
                 getUser·p0.999:  25.370 ms/op
                 getUser·p0.9999: 30.223 ms/op
                 getUser·p1.00:   36.176 ms/op

Iteration   2: 5.607 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.911 ms/op
                 getUser·p0.50:   5.194 ms/op
                 getUser·p0.90:   7.143 ms/op
                 getUser·p0.95:   8.585 ms/op
                 getUser·p0.99:   12.298 ms/op
                 getUser·p0.999:  20.906 ms/op
                 getUser·p0.9999: 27.731 ms/op
                 getUser·p1.00:   28.901 ms/op

Iteration   3: 5.587 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.380 ms/op
                 getUser·p0.50:   5.325 ms/op
                 getUser·p0.90:   6.832 ms/op
                 getUser·p0.95:   7.635 ms/op
                 getUser·p0.99:   9.748 ms/op
                 getUser·p0.999:  29.068 ms/op
                 getUser·p0.9999: 34.031 ms/op
                 getUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 171113
  mean =      5.611 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 64040 
    [ 5.000,  7.500) = 93722 
    [ 7.500, 10.000) = 10227 
    [10.000, 12.500) = 1784 
    [12.500, 15.000) = 765 
    [15.000, 17.500) = 262 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.911 ms/op
     p(50.0000) =      5.243 ms/op
     p(90.0000) =      7.094 ms/op
     p(95.0000) =      8.266 ms/op
     p(99.0000) =     11.696 ms/op
     p(99.9000) =     24.090 ms/op
     p(99.9900) =     33.092 ms/op
     p(99.9990) =     36.129 ms/op
     p(99.9999) =     36.176 ms/op
    p(100.0000) =     36.176 ms/op


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
# Warmup Iteration   1: 20.833 ±(99.9%) 0.375 ms/op
# Warmup Iteration   2: 7.670 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.947 ±(99.9%) 0.028 ms/op
Iteration   1: 6.854 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   6.521 ms/op
                 listUser·p0.90:   8.438 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   12.319 ms/op
                 listUser·p0.999:  28.092 ms/op
                 listUser·p0.9999: 34.908 ms/op
                 listUser·p1.00:   36.110 ms/op

Iteration   2: 6.813 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.858 ms/op
                 listUser·p0.50:   6.406 ms/op
                 listUser·p0.90:   8.421 ms/op
                 listUser·p0.95:   9.454 ms/op
                 listUser·p0.99:   12.533 ms/op
                 listUser·p0.999:  31.147 ms/op
                 listUser·p0.9999: 37.023 ms/op
                 listUser·p1.00:   37.880 ms/op

Iteration   3: 6.731 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   6.349 ms/op
                 listUser·p0.90:   8.290 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   13.572 ms/op
                 listUser·p0.999:  22.073 ms/op
                 listUser·p0.9999: 32.907 ms/op
                 listUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141175
  mean =      6.799 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 3463 
    [ 5.000,  7.500) = 109488 
    [ 7.500, 10.000) = 22789 
    [10.000, 12.500) = 3834 
    [12.500, 15.000) = 952 
    [15.000, 17.500) = 275 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 76 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.858 ms/op
     p(50.0000) =      6.423 ms/op
     p(90.0000) =      8.389 ms/op
     p(95.0000) =      9.486 ms/op
     p(99.0000) =     12.861 ms/op
     p(99.9000) =     28.339 ms/op
     p(99.9900) =     36.002 ms/op
     p(99.9990) =     37.853 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.714 ± 1.285  ops/ms
ClientPb.existUser                       thrpt       3   5.838 ± 3.487  ops/ms
ClientPb.getUser                         thrpt       3   5.584 ± 2.335  ops/ms
ClientPb.listUser                        thrpt       3   4.742 ± 3.311  ops/ms
ClientPb.createUser                       avgt       3   5.769 ± 0.669   ms/op
ClientPb.existUser                        avgt       3   5.576 ± 2.995   ms/op
ClientPb.getUser                          avgt       3   5.757 ± 1.582   ms/op
ClientPb.listUser                         avgt       3   6.748 ± 2.628   ms/op
ClientPb.createUser                     sample  169836   5.651 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.788           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.971           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.807           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.519           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.061           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.012           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.322           ms/op
ClientPb.existUser                      sample  178394   5.377 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.042           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.087           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.758           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.537           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.633           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.107           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.986           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.127           ms/op
ClientPb.getUser                        sample  171113   5.611 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.911           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.243           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.094           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.266           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.696           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.090           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.092           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.176           ms/op
ClientPb.listUser                       sample  141175   6.799 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.858           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.423           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.389           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.486           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.861           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.339           ms/op
ClientPb.listUser:listUser·p0.9999      sample          36.002           ms/op
ClientPb.listUser:listUser·p1.00        sample          37.880           ms/op
