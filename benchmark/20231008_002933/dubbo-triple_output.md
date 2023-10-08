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
# Warmup Iteration   1: 1.839 ops/ms
# Warmup Iteration   2: 4.653 ops/ms
# Warmup Iteration   3: 8.431 ops/ms
Iteration   1: 8.796 ops/ms
Iteration   2: 8.929 ops/ms
Iteration   3: 9.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.987 ±(99.9%) 4.129 ops/ms [Average]
  (min, avg, max) = (8.796, 8.987, 9.237), stdev = 0.226
  CI (99.9%): [4.858, 13.117] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.740 ops/ms
# Warmup Iteration   2: 8.790 ops/ms
# Warmup Iteration   3: 9.375 ops/ms
Iteration   1: 9.595 ops/ms
Iteration   2: 9.733 ops/ms
Iteration   3: 9.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.630 ±(99.9%) 1.657 ops/ms [Average]
  (min, avg, max) = (9.561, 9.630, 9.733), stdev = 0.091
  CI (99.9%): [7.973, 11.286] (assumes normal distribution)


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
# Warmup Iteration   1: 2.916 ops/ms
# Warmup Iteration   2: 7.503 ops/ms
# Warmup Iteration   3: 8.588 ops/ms
Iteration   1: 8.887 ops/ms
Iteration   2: 9.050 ops/ms
Iteration   3: 9.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.006 ±(99.9%) 1.901 ops/ms [Average]
  (min, avg, max) = (8.887, 9.006, 9.081), stdev = 0.104
  CI (99.9%): [7.105, 10.907] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.470 ops/ms
# Warmup Iteration   2: 6.987 ops/ms
# Warmup Iteration   3: 7.644 ops/ms
Iteration   1: 7.554 ops/ms
Iteration   2: 7.832 ops/ms
Iteration   3: 7.714 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.700 ±(99.9%) 2.547 ops/ms [Average]
  (min, avg, max) = (7.554, 7.700, 7.832), stdev = 0.140
  CI (99.9%): [5.153, 10.247] (assumes normal distribution)


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
# Warmup Iteration   1: 11.556 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.563 ±(99.9%) 0.004 ms/op
Iteration   1: 3.528 ±(99.9%) 0.007 ms/op
Iteration   2: 3.496 ±(99.9%) 0.004 ms/op
Iteration   3: 3.549 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.524 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (3.496, 3.524, 3.549), stdev = 0.027
  CI (99.9%): [3.037, 4.011] (assumes normal distribution)


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
# Warmup Iteration   1: 8.843 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.004 ms/op
Iteration   1: 3.347 ±(99.9%) 0.004 ms/op
Iteration   2: 3.430 ±(99.9%) 0.007 ms/op
Iteration   3: 3.412 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.396 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (3.347, 3.396, 3.430), stdev = 0.044
  CI (99.9%): [2.598, 4.195] (assumes normal distribution)


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
# Warmup Iteration   1: 10.677 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.800 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.699 ±(99.9%) 0.004 ms/op
Iteration   1: 3.615 ±(99.9%) 0.006 ms/op
Iteration   2: 3.529 ±(99.9%) 0.004 ms/op
Iteration   3: 3.473 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.539 ±(99.9%) 1.305 ms/op [Average]
  (min, avg, max) = (3.473, 3.539, 3.615), stdev = 0.072
  CI (99.9%): [2.234, 4.843] (assumes normal distribution)


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
# Warmup Iteration   1: 12.304 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.567 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.211 ±(99.9%) 0.006 ms/op
Iteration   1: 4.225 ±(99.9%) 0.006 ms/op
Iteration   2: 4.091 ±(99.9%) 0.005 ms/op
Iteration   3: 4.170 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.162 ±(99.9%) 1.222 ms/op [Average]
  (min, avg, max) = (4.091, 4.162, 4.225), stdev = 0.067
  CI (99.9%): [2.940, 5.384] (assumes normal distribution)


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
# Warmup Iteration   1: 10.232 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 3.919 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.011 ms/op
Iteration   1: 3.792 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   6.234 ms/op
                 createUser·p0.99:   8.135 ms/op
                 createUser·p0.999:  13.750 ms/op
                 createUser·p0.9999: 23.527 ms/op
                 createUser·p1.00:   24.183 ms/op

Iteration   2: 3.499 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   7.094 ms/op
                 createUser·p0.999:  21.912 ms/op
                 createUser·p0.9999: 25.948 ms/op
                 createUser·p1.00:   27.197 ms/op

Iteration   3: 3.598 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  23.036 ms/op
                 createUser·p0.9999: 31.228 ms/op
                 createUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 264482
  mean =      3.626 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4656 
    [ 2.500,  5.000) = 247618 
    [ 5.000,  7.500) = 9180 
    [ 7.500, 10.000) = 2079 
    [10.000, 12.500) = 385 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     20.891 ms/op
     p(99.9900) =     27.117 ms/op
     p(99.9990) =     31.662 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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
# Warmup Iteration   1: 10.625 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.010 ms/op
Iteration   1: 3.388 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.518 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   6.119 ms/op
                 existUser·p0.999:  19.628 ms/op
                 existUser·p0.9999: 22.571 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   2: 3.394 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.706 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   7.224 ms/op
                 existUser·p0.999:  20.702 ms/op
                 existUser·p0.9999: 24.464 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   3: 3.474 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.735 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  10.875 ms/op
                 existUser·p0.9999: 26.010 ms/op
                 existUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280846
  mean =      3.418 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7301 
    [ 2.500,  5.000) = 265907 
    [ 5.000,  7.500) = 6138 
    [ 7.500, 10.000) = 987 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 113 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.518 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     16.151 ms/op
     p(99.9900) =     25.065 ms/op
     p(99.9990) =     26.385 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 11.743 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.655 ±(99.9%) 0.011 ms/op
Iteration   1: 3.633 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   3.441 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  20.054 ms/op
                 getUser·p0.9999: 23.076 ms/op
                 getUser·p1.00:   26.411 ms/op

Iteration   2: 3.532 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.671 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  21.494 ms/op
                 getUser·p0.9999: 28.279 ms/op
                 getUser·p1.00:   29.131 ms/op

Iteration   3: 3.511 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.686 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  16.176 ms/op
                 getUser·p0.9999: 26.309 ms/op
                 getUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 269530
  mean =      3.558 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3285 
    [ 2.500,  5.000) = 256787 
    [ 5.000,  7.500) = 7668 
    [ 7.500, 10.000) = 971 
    [10.000, 12.500) = 362 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 41 

  Percentiles, ms/op:
      p(0.0000) =      1.612 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     18.726 ms/op
     p(99.9900) =     26.676 ms/op
     p(99.9990) =     28.772 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 11.654 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.842 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.298 ±(99.9%) 0.014 ms/op
Iteration   1: 4.289 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.786 ms/op
                 listUser·p0.50:   4.076 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  21.539 ms/op
                 listUser·p0.9999: 24.561 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   2: 4.122 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.769 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  15.958 ms/op
                 listUser·p0.9999: 18.153 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   3: 4.251 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  15.540 ms/op
                 listUser·p0.9999: 18.967 ms/op
                 listUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227571
  mean =      4.220 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 214236 
    [ 5.000,  7.500) = 9543 
    [ 7.500, 10.000) = 2626 
    [10.000, 12.500) = 489 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 242 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.769 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     16.024 ms/op
     p(99.9900) =     23.798 ms/op
     p(99.9990) =     25.648 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.987 ± 4.129  ops/ms
ClientPb.existUser                       thrpt       3   9.630 ± 1.657  ops/ms
ClientPb.getUser                         thrpt       3   9.006 ± 1.901  ops/ms
ClientPb.listUser                        thrpt       3   7.700 ± 2.547  ops/ms
ClientPb.createUser                       avgt       3   3.524 ± 0.487   ms/op
ClientPb.existUser                        avgt       3   3.396 ± 0.798   ms/op
ClientPb.getUser                          avgt       3   3.539 ± 1.305   ms/op
ClientPb.listUser                         avgt       3   4.162 ± 1.222   ms/op
ClientPb.createUser                     sample  264482   3.626 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.837           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.404           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.194           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.801           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.692           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.891           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.117           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.113           ms/op
ClientPb.existUser                      sample  280846   3.418 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.518           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.281           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.668           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.151           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.065           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.444           ms/op
ClientPb.getUser                        sample  269530   3.558 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.612           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.412           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.094           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.726           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.676           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.131           ms/op
ClientPb.listUser                       sample  227571   4.220 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.769           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.161           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.024           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.798           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.788           ms/op
