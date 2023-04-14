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
# Warmup Iteration   1: 2.102 ops/ms
# Warmup Iteration   2: 5.294 ops/ms
# Warmup Iteration   3: 8.529 ops/ms
Iteration   1: 9.184 ops/ms
Iteration   2: 8.863 ops/ms
Iteration   3: 8.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.007 ±(99.9%) 2.970 ops/ms [Average]
  (min, avg, max) = (8.863, 9.007, 9.184), stdev = 0.163
  CI (99.9%): [6.037, 11.977] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.594 ops/ms
# Warmup Iteration   2: 9.013 ops/ms
# Warmup Iteration   3: 9.611 ops/ms
Iteration   1: 9.844 ops/ms
Iteration   2: 10.026 ops/ms
Iteration   3: 9.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.726 ±(99.9%) 6.820 ops/ms [Average]
  (min, avg, max) = (9.307, 9.726, 10.026), stdev = 0.374
  CI (99.9%): [2.905, 16.546] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.738 ops/ms
# Warmup Iteration   2: 8.256 ops/ms
# Warmup Iteration   3: 9.005 ops/ms
Iteration   1: 9.444 ops/ms
Iteration   2: 9.254 ops/ms
Iteration   3: 9.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.364 ±(99.9%) 1.795 ops/ms [Average]
  (min, avg, max) = (9.254, 9.364, 9.444), stdev = 0.098
  CI (99.9%): [7.569, 11.160] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.935 ops/ms
# Warmup Iteration   2: 7.010 ops/ms
# Warmup Iteration   3: 7.689 ops/ms
Iteration   1: 7.730 ops/ms
Iteration   2: 8.191 ops/ms
Iteration   3: 7.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.970 ±(99.9%) 4.216 ops/ms [Average]
  (min, avg, max) = (7.730, 7.970, 8.191), stdev = 0.231
  CI (99.9%): [3.754, 12.186] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.369 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.858 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.673 ±(99.9%) 0.008 ms/op
Iteration   1: 3.461 ±(99.9%) 0.007 ms/op
Iteration   2: 3.442 ±(99.9%) 0.010 ms/op
Iteration   3: 3.446 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.450 ±(99.9%) 0.179 ms/op [Average]
  (min, avg, max) = (3.442, 3.450, 3.461), stdev = 0.010
  CI (99.9%): [3.270, 3.629] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.992 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.530 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.356 ±(99.9%) 0.008 ms/op
Iteration   1: 3.310 ±(99.9%) 0.011 ms/op
Iteration   2: 3.309 ±(99.9%) 0.004 ms/op
Iteration   3: 3.257 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.292 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (3.257, 3.292, 3.310), stdev = 0.030
  CI (99.9%): [2.736, 3.848] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.727 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.531 ±(99.9%) 0.002 ms/op
Iteration   1: 3.479 ±(99.9%) 0.005 ms/op
Iteration   2: 3.458 ±(99.9%) 0.010 ms/op
Iteration   3: 3.431 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.456 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (3.431, 3.456, 3.479), stdev = 0.024
  CI (99.9%): [3.017, 3.895] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.207 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.000 ±(99.9%) 0.013 ms/op
Iteration   1: 4.131 ±(99.9%) 0.008 ms/op
Iteration   2: 4.030 ±(99.9%) 0.009 ms/op
Iteration   3: 3.942 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.034 ±(99.9%) 1.725 ms/op [Average]
  (min, avg, max) = (3.942, 4.034, 4.131), stdev = 0.095
  CI (99.9%): [2.309, 5.759] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.310 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.010 ms/op
Iteration   1: 3.385 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.526 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  21.315 ms/op
                 createUser·p0.9999: 24.332 ms/op
                 createUser·p1.00:   24.609 ms/op

Iteration   2: 3.602 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   6.712 ms/op
                 createUser·p0.999:  24.423 ms/op
                 createUser·p0.9999: 26.575 ms/op
                 createUser·p1.00:   30.671 ms/op

Iteration   3: 3.525 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.206 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.387 ms/op
                 createUser·p0.99:   6.693 ms/op
                 createUser·p0.999:  21.050 ms/op
                 createUser·p0.9999: 31.228 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273946
  mean =      3.502 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8964 
    [ 2.500,  5.000) = 255675 
    [ 5.000,  7.500) = 7823 
    [ 7.500, 10.000) = 839 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 153 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     22.055 ms/op
     p(99.9900) =     26.627 ms/op
     p(99.9990) =     31.400 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.822 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.517 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.354 ±(99.9%) 0.010 ms/op
Iteration   1: 3.502 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  19.684 ms/op
                 existUser·p0.9999: 22.573 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   2: 3.614 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.602 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   6.521 ms/op
                 existUser·p0.99:   8.337 ms/op
                 existUser·p0.999:  16.081 ms/op
                 existUser·p0.9999: 46.606 ms/op
                 existUser·p1.00:   47.317 ms/op

Iteration   3: 3.356 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.955 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.969 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   6.390 ms/op
                 existUser·p0.999:  12.693 ms/op
                 existUser·p0.9999: 27.704 ms/op
                 existUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 275127
  mean =      3.487 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 260529 
    [ 5.000, 10.000) = 13870 
    [10.000, 15.000) = 468 
    [15.000, 20.000) = 42 
    [20.000, 25.000) = 127 
    [25.000, 30.000) = 59 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     14.082 ms/op
     p(99.9900) =     43.450 ms/op
     p(99.9990) =     47.071 ms/op
     p(99.9999) =     47.317 ms/op
    p(100.0000) =     47.317 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.363 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.011 ms/op
Iteration   1: 3.564 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   7.597 ms/op
                 getUser·p0.999:  11.690 ms/op
                 getUser·p0.9999: 22.873 ms/op
                 getUser·p1.00:   23.757 ms/op

Iteration   2: 3.430 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.513 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  22.171 ms/op
                 getUser·p0.9999: 26.214 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 3.428 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  21.291 ms/op
                 getUser·p0.9999: 30.802 ms/op
                 getUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276261
  mean =      3.473 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 878 
    [ 2.500,  5.000) = 265188 
    [ 5.000,  7.500) = 8584 
    [ 7.500, 10.000) = 1154 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 106 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     12.438 ms/op
     p(99.9900) =     29.536 ms/op
     p(99.9990) =     30.995 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.044 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.456 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.111 ±(99.9%) 0.015 ms/op
Iteration   1: 4.116 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.497 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 25.195 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 4.060 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.886 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   8.192 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 23.957 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   3: 4.012 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.728 ms/op
                 listUser·p0.999:  15.335 ms/op
                 listUser·p0.9999: 19.695 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236249
  mean =      4.062 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 224649 
    [ 5.000,  7.500) = 8419 
    [ 7.500, 10.000) = 2251 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     15.876 ms/op
     p(99.9900) =     24.252 ms/op
     p(99.9990) =     27.731 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.007 ± 2.970  ops/ms
ClientPb.existUser                       thrpt       3   9.726 ± 6.820  ops/ms
ClientPb.getUser                         thrpt       3   9.364 ± 1.795  ops/ms
ClientPb.listUser                        thrpt       3   7.970 ± 4.216  ops/ms
ClientPb.createUser                       avgt       3   3.450 ± 0.179   ms/op
ClientPb.existUser                        avgt       3   3.292 ± 0.556   ms/op
ClientPb.getUser                          avgt       3   3.456 ± 0.439   ms/op
ClientPb.listUser                         avgt       3   4.034 ± 1.725   ms/op
ClientPb.createUser                     sample  273946   3.502 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.206           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.448           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.537           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.055           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.627           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.047           ms/op
ClientPb.existUser                      sample  275127   3.487 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.955           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.157           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.218           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.176           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.082           ms/op
ClientPb.existUser:existUser·p0.9999    sample          43.450           ms/op
ClientPb.existUser:existUser·p1.00      sample          47.317           ms/op
ClientPb.getUser                        sample  276261   3.473 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.333           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.314           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.824           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.438           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.536           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.850           ms/op
ClientPb.listUser                       sample  236249   4.062 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.497           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.897           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.252           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.787           ms/op
