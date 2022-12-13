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
# Warmup Iteration   1: 1.203 ops/ms
# Warmup Iteration   2: 2.475 ops/ms
# Warmup Iteration   3: 5.581 ops/ms
Iteration   1: 5.923 ops/ms
Iteration   2: 5.895 ops/ms
Iteration   3: 6.061 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.960 ±(99.9%) 1.618 ops/ms [Average]
  (min, avg, max) = (5.895, 5.960, 6.061), stdev = 0.089
  CI (99.9%): [4.341, 7.578] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.796 ops/ms
# Warmup Iteration   2: 5.300 ops/ms
# Warmup Iteration   3: 6.120 ops/ms
Iteration   1: 6.147 ops/ms
Iteration   2: 6.103 ops/ms
Iteration   3: 6.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.111 ±(99.9%) 0.593 ops/ms [Average]
  (min, avg, max) = (6.083, 6.111, 6.147), stdev = 0.033
  CI (99.9%): [5.518, 6.704] (assumes normal distribution)


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
# Warmup Iteration   1: 1.570 ops/ms
# Warmup Iteration   2: 4.936 ops/ms
# Warmup Iteration   3: 6.164 ops/ms
Iteration   1: 5.614 ops/ms
Iteration   2: 5.676 ops/ms
Iteration   3: 5.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.690 ±(99.9%) 1.531 ops/ms [Average]
  (min, avg, max) = (5.614, 5.690, 5.780), stdev = 0.084
  CI (99.9%): [4.159, 7.221] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.543 ops/ms
# Warmup Iteration   2: 3.852 ops/ms
# Warmup Iteration   3: 4.793 ops/ms
Iteration   1: 4.760 ops/ms
Iteration   2: 4.802 ops/ms
Iteration   3: 4.994 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.852 ±(99.9%) 2.270 ops/ms [Average]
  (min, avg, max) = (4.760, 4.852, 4.994), stdev = 0.124
  CI (99.9%): [2.582, 7.122] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 20.205 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 7.264 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.886 ±(99.9%) 0.011 ms/op
Iteration   1: 5.875 ±(99.9%) 0.009 ms/op
Iteration   2: 5.867 ±(99.9%) 0.021 ms/op
Iteration   3: 5.588 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.777 ±(99.9%) 2.975 ms/op [Average]
  (min, avg, max) = (5.588, 5.777, 5.875), stdev = 0.163
  CI (99.9%): [2.801, 8.752] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 17.198 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.933 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.185 ±(99.9%) 0.018 ms/op
Iteration   1: 5.378 ±(99.9%) 0.013 ms/op
Iteration   2: 5.327 ±(99.9%) 0.012 ms/op
Iteration   3: 5.252 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.319 ±(99.9%) 1.150 ms/op [Average]
  (min, avg, max) = (5.252, 5.319, 5.378), stdev = 0.063
  CI (99.9%): [4.169, 6.469] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 17.248 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 7.075 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.531 ±(99.9%) 0.010 ms/op
Iteration   1: 5.852 ±(99.9%) 0.010 ms/op
Iteration   2: 5.459 ±(99.9%) 0.012 ms/op
Iteration   3: 5.257 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.523 ±(99.9%) 5.519 ms/op [Average]
  (min, avg, max) = (5.257, 5.523, 5.852), stdev = 0.303
  CI (99.9%): [0.003, 11.042] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 18.221 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 7.158 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.188 ±(99.9%) 0.022 ms/op
Iteration   1: 6.336 ±(99.9%) 0.020 ms/op
Iteration   2: 6.378 ±(99.9%) 0.016 ms/op
Iteration   3: 6.206 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.307 ±(99.9%) 1.636 ms/op [Average]
  (min, avg, max) = (6.206, 6.307, 6.378), stdev = 0.090
  CI (99.9%): [4.670, 7.943] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.631 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 8.076 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 6.151 ±(99.9%) 0.031 ms/op
Iteration   1: 5.709 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.187 ms/op
                 createUser·p0.50:   5.415 ms/op
                 createUser·p0.90:   7.291 ms/op
                 createUser·p0.95:   8.225 ms/op
                 createUser·p0.99:   10.290 ms/op
                 createUser·p0.999:  19.137 ms/op
                 createUser·p0.9999: 29.989 ms/op
                 createUser·p1.00:   32.506 ms/op

Iteration   2: 5.590 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.085 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   6.824 ms/op
                 createUser·p0.95:   7.684 ms/op
                 createUser·p0.99:   10.732 ms/op
                 createUser·p0.999:  26.739 ms/op
                 createUser·p0.9999: 30.501 ms/op
                 createUser·p1.00:   31.490 ms/op

Iteration   3: 5.810 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.384 ms/op
                 createUser·p0.50:   5.472 ms/op
                 createUser·p0.90:   7.274 ms/op
                 createUser·p0.95:   8.389 ms/op
                 createUser·p0.99:   11.090 ms/op
                 createUser·p0.999:  32.833 ms/op
                 createUser·p0.9999: 37.650 ms/op
                 createUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 168256
  mean =      5.702 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 50469 
    [ 5.000,  7.500) = 104863 
    [ 7.500, 10.000) = 10398 
    [10.000, 12.500) = 1730 
    [12.500, 15.000) = 457 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      2.085 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.119 ms/op
     p(95.0000) =      8.126 ms/op
     p(99.0000) =     10.633 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     35.794 ms/op
     p(99.9990) =     38.157 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 17.763 ±(99.9%) 0.280 ms/op
# Warmup Iteration   2: 6.067 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.382 ±(99.9%) 0.020 ms/op
Iteration   1: 5.146 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.261 ms/op
                 existUser·p0.50:   4.841 ms/op
                 existUser·p0.90:   6.382 ms/op
                 existUser·p0.95:   7.463 ms/op
                 existUser·p0.99:   10.125 ms/op
                 existUser·p0.999:  25.120 ms/op
                 existUser·p0.9999: 30.971 ms/op
                 existUser·p1.00:   32.145 ms/op

Iteration   2: 5.177 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.101 ms/op
                 existUser·p0.50:   5.005 ms/op
                 existUser·p0.90:   6.332 ms/op
                 existUser·p0.95:   6.906 ms/op
                 existUser·p0.99:   8.552 ms/op
                 existUser·p0.999:  12.451 ms/op
                 existUser·p0.9999: 29.106 ms/op
                 existUser·p1.00:   29.426 ms/op

Iteration   3: 5.010 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.126 ms/op
                 existUser·p0.50:   4.809 ms/op
                 existUser·p0.90:   5.997 ms/op
                 existUser·p0.95:   6.611 ms/op
                 existUser·p0.99:   8.880 ms/op
                 existUser·p0.999:  27.617 ms/op
                 existUser·p0.9999: 31.195 ms/op
                 existUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 187715
  mean =      5.110 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 99 
    [ 2.500,  5.000) = 105654 
    [ 5.000,  7.500) = 75780 
    [ 7.500, 10.000) = 4987 
    [10.000, 12.500) = 815 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 68 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.101 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      6.234 ms/op
     p(95.0000) =      6.963 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     15.078 ms/op
     p(99.9900) =     30.966 ms/op
     p(99.9990) =     32.002 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 17.542 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 7.069 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 5.577 ±(99.9%) 0.019 ms/op
Iteration   1: 5.417 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.679 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.495 ms/op
                 getUser·p0.95:   7.684 ms/op
                 getUser·p0.99:   10.486 ms/op
                 getUser·p0.999:  15.925 ms/op
                 getUser·p0.9999: 26.345 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   2: 5.433 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   5.210 ms/op
                 getUser·p0.90:   6.496 ms/op
                 getUser·p0.95:   7.537 ms/op
                 getUser·p0.99:   9.716 ms/op
                 getUser·p0.999:  26.815 ms/op
                 getUser·p0.9999: 29.452 ms/op
                 getUser·p1.00:   30.704 ms/op

Iteration   3: 5.486 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.494 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   6.758 ms/op
                 getUser·p0.95:   7.627 ms/op
                 getUser·p0.99:   9.896 ms/op
                 getUser·p0.999:  28.131 ms/op
                 getUser·p0.9999: 32.802 ms/op
                 getUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176118
  mean =      5.445 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 67713 
    [ 5.000,  7.500) = 98950 
    [ 7.500, 10.000) = 7656 
    [10.000, 12.500) = 1286 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.118 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      6.595 ms/op
     p(95.0000) =      7.619 ms/op
     p(99.0000) =     10.040 ms/op
     p(99.9000) =     23.884 ms/op
     p(99.9900) =     31.261 ms/op
     p(99.9990) =     33.511 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.838 ±(99.9%) 0.339 ms/op
# Warmup Iteration   2: 7.979 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.915 ±(99.9%) 0.031 ms/op
Iteration   1: 6.560 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.654 ms/op
                 listUser·p0.50:   6.259 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   12.315 ms/op
                 listUser·p0.999:  26.101 ms/op
                 listUser·p0.9999: 28.644 ms/op
                 listUser·p1.00:   29.590 ms/op

Iteration   2: 6.545 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   6.291 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   11.469 ms/op
                 listUser·p0.999:  27.333 ms/op
                 listUser·p0.9999: 31.101 ms/op
                 listUser·p1.00:   32.309 ms/op

Iteration   3: 6.224 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.261 ms/op
                 listUser·p0.50:   5.882 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   12.698 ms/op
                 listUser·p0.999:  25.450 ms/op
                 listUser·p0.9999: 29.192 ms/op
                 listUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148917
  mean =      6.439 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 6689 
    [ 5.000,  7.500) = 124887 
    [ 7.500, 10.000) = 13428 
    [10.000, 12.500) = 2642 
    [12.500, 15.000) = 670 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 120 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.138 ms/op
     p(50.0000) =      6.136 ms/op
     p(90.0000) =      7.684 ms/op
     p(95.0000) =      8.765 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     26.509 ms/op
     p(99.9900) =     29.768 ms/op
     p(99.9990) =     32.213 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.960 ± 1.618  ops/ms
ClientPb.existUser                       thrpt       3   6.111 ± 0.593  ops/ms
ClientPb.getUser                         thrpt       3   5.690 ± 1.531  ops/ms
ClientPb.listUser                        thrpt       3   4.852 ± 2.270  ops/ms
ClientPb.createUser                       avgt       3   5.777 ± 2.975   ms/op
ClientPb.existUser                        avgt       3   5.319 ± 1.150   ms/op
ClientPb.getUser                          avgt       3   5.523 ± 5.519   ms/op
ClientPb.listUser                         avgt       3   6.307 ± 1.636   ms/op
ClientPb.createUser                     sample  168256   5.702 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.085           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.119           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.126           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.633           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.628           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.794           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.470           ms/op
ClientPb.existUser                      sample  187715   5.110 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.101           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.882           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.234           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.963           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.241           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.078           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.966           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.145           ms/op
ClientPb.getUser                        sample  176118   5.445 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.118           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.202           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.595           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.619           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.040           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.884           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.261           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.210           ms/op
ClientPb.listUser                       sample  148917   6.439 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.138           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.136           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.684           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.765           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.141           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.509           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.768           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.309           ms/op
