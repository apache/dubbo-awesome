# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.815 ops/ms
# Warmup Iteration   2: 5.042 ops/ms
# Warmup Iteration   3: 8.555 ops/ms
Iteration   1: 8.781 ops/ms
Iteration   2: 9.236 ops/ms
Iteration   3: 9.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.162 ±(99.9%) 6.392 ops/ms [Average]
  (min, avg, max) = (8.781, 9.162, 9.470), stdev = 0.350
  CI (99.9%): [2.770, 15.554] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.647 ops/ms
# Warmup Iteration   2: 8.005 ops/ms
# Warmup Iteration   3: 9.186 ops/ms
Iteration   1: 9.878 ops/ms
Iteration   2: 9.816 ops/ms
Iteration   3: 9.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.767 ±(99.9%) 2.603 ops/ms [Average]
  (min, avg, max) = (9.606, 9.767, 9.878), stdev = 0.143
  CI (99.9%): [7.164, 12.369] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.644 ops/ms
# Warmup Iteration   2: 7.863 ops/ms
# Warmup Iteration   3: 9.425 ops/ms
Iteration   1: 9.322 ops/ms
Iteration   2: 9.507 ops/ms
Iteration   3: 9.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.395 ±(99.9%) 1.798 ops/ms [Average]
  (min, avg, max) = (9.322, 9.395, 9.507), stdev = 0.099
  CI (99.9%): [7.597, 11.192] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.819 ops/ms
# Warmup Iteration   2: 7.125 ops/ms
# Warmup Iteration   3: 7.882 ops/ms
Iteration   1: 8.087 ops/ms
Iteration   2: 7.917 ops/ms
Iteration   3: 8.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.022 ±(99.9%) 1.665 ops/ms [Average]
  (min, avg, max) = (7.917, 8.022, 8.087), stdev = 0.091
  CI (99.9%): [6.357, 9.687] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.979 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.768 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.407 ±(99.9%) 0.010 ms/op
Iteration   1: 3.468 ±(99.9%) 0.004 ms/op
Iteration   2: 3.433 ±(99.9%) 0.005 ms/op
Iteration   3: 3.479 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.460 ±(99.9%) 0.437 ms/op [Average]
  (min, avg, max) = (3.433, 3.460, 3.479), stdev = 0.024
  CI (99.9%): [3.023, 3.897] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.907 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.307 ±(99.9%) 0.006 ms/op
Iteration   1: 3.205 ±(99.9%) 0.008 ms/op
Iteration   2: 3.135 ±(99.9%) 0.011 ms/op
Iteration   3: 3.207 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.182 ±(99.9%) 0.741 ms/op [Average]
  (min, avg, max) = (3.135, 3.182, 3.207), stdev = 0.041
  CI (99.9%): [2.441, 3.923] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.410 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.607 ±(99.9%) 0.005 ms/op
Iteration   1: 3.508 ±(99.9%) 0.008 ms/op
Iteration   2: 3.461 ±(99.9%) 0.010 ms/op
Iteration   3: 3.459 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.476 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (3.459, 3.476, 3.508), stdev = 0.028
  CI (99.9%): [2.971, 3.981] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.319 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.148 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.010 ms/op
Iteration   1: 4.003 ±(99.9%) 0.008 ms/op
Iteration   2: 3.917 ±(99.9%) 0.010 ms/op
Iteration   3: 3.991 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.970 ±(99.9%) 0.847 ms/op [Average]
  (min, avg, max) = (3.917, 3.970, 4.003), stdev = 0.046
  CI (99.9%): [3.124, 4.817] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.512 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.888 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.009 ms/op
Iteration   1: 3.293 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.071 ms/op
                 createUser·p0.999:  18.247 ms/op
                 createUser·p0.9999: 29.435 ms/op
                 createUser·p1.00:   30.015 ms/op

Iteration   2: 3.480 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.546 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  24.132 ms/op
                 createUser·p0.9999: 26.438 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   3: 3.425 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.597 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.570 ms/op
                 createUser·p0.999:  20.578 ms/op
                 createUser·p0.9999: 25.526 ms/op
                 createUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282257
  mean =      3.397 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4838 
    [ 2.500,  5.000) = 270705 
    [ 5.000,  7.500) = 5665 
    [ 7.500, 10.000) = 603 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.226 ms/op
     p(99.9000) =     20.734 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     29.929 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.990 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.499 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.009 ms/op
Iteration   1: 3.345 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.139 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  19.348 ms/op
                 existUser·p0.9999: 23.393 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   2: 3.269 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.550 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  9.486 ms/op
                 existUser·p0.9999: 26.091 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   3: 3.329 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  19.379 ms/op
                 existUser·p0.9999: 28.501 ms/op
                 existUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289410
  mean =      3.314 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6908 
    [ 2.500,  5.000) = 277657 
    [ 5.000,  7.500) = 3962 
    [ 7.500, 10.000) = 465 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     12.019 ms/op
     p(99.9900) =     26.752 ms/op
     p(99.9990) =     29.557 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.538 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.010 ms/op
Iteration   1: 3.617 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.559 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   5.505 ms/op
                 getUser·p0.99:   7.528 ms/op
                 getUser·p0.999:  18.448 ms/op
                 getUser·p0.9999: 23.122 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   2: 3.568 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  21.543 ms/op
                 getUser·p0.9999: 24.054 ms/op
                 getUser·p1.00:   24.576 ms/op

Iteration   3: 3.605 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.559 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   6.578 ms/op
                 getUser·p0.999:  23.156 ms/op
                 getUser·p0.9999: 33.526 ms/op
                 getUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 266729
  mean =      3.597 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12152 
    [ 2.500,  5.000) = 240870 
    [ 5.000,  7.500) = 11945 
    [ 7.500, 10.000) = 1251 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 41 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     19.399 ms/op
     p(99.9900) =     32.702 ms/op
     p(99.9990) =     33.904 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.058 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.492 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.013 ms/op
Iteration   1: 4.002 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.599 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.104 ms/op
                 listUser·p0.99:   7.930 ms/op
                 listUser·p0.999:  23.921 ms/op
                 listUser·p0.9999: 29.098 ms/op
                 listUser·p1.00:   29.753 ms/op

Iteration   2: 4.073 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.243 ms/op
                 listUser·p0.99:   8.020 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   24.183 ms/op

Iteration   3: 3.945 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.540 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  15.598 ms/op
                 listUser·p0.9999: 18.369 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239685
  mean =      4.006 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 227498 
    [ 5.000,  7.500) = 9487 
    [ 7.500, 10.000) = 1754 
    [10.000, 12.500) = 372 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     16.498 ms/op
     p(99.9900) =     27.886 ms/op
     p(99.9990) =     29.695 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.162 ± 6.392  ops/ms
ClientPb.existUser                       thrpt       3   9.767 ± 2.603  ops/ms
ClientPb.getUser                         thrpt       3   9.395 ± 1.798  ops/ms
ClientPb.listUser                        thrpt       3   8.022 ± 1.665  ops/ms
ClientPb.createUser                       avgt       3   3.460 ± 0.437   ms/op
ClientPb.existUser                        avgt       3   3.182 ± 0.741   ms/op
ClientPb.getUser                          avgt       3   3.476 ± 0.505   ms/op
ClientPb.listUser                         avgt       3   3.970 ± 0.847   ms/op
ClientPb.createUser                     sample  282257   3.397 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.276           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.879           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.226           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.734           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.639           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.015           ms/op
ClientPb.existUser                      sample  289410   3.314 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.102           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.707           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.022           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.019           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.752           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.590           ms/op
ClientPb.getUser                        sample  266729   3.597 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.264           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.432           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.243           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.046           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.053           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.399           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.702           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.603           ms/op
ClientPb.listUser                       sample  239685   4.006 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.816           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.014           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.692           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.498           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.886           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.753           ms/op
