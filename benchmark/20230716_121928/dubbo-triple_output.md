# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.698 ops/ms
# Warmup Iteration   2: 3.951 ops/ms
# Warmup Iteration   3: 8.491 ops/ms
Iteration   1: 8.017 ops/ms
Iteration   2: 8.626 ops/ms
Iteration   3: 8.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.368 ±(99.9%) 5.750 ops/ms [Average]
  (min, avg, max) = (8.017, 8.368, 8.626), stdev = 0.315
  CI (99.9%): [2.618, 14.118] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.941 ops/ms
# Warmup Iteration   2: 8.114 ops/ms
# Warmup Iteration   3: 8.707 ops/ms
Iteration   1: 8.710 ops/ms
Iteration   2: 9.134 ops/ms
Iteration   3: 9.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.021 ±(99.9%) 4.982 ops/ms [Average]
  (min, avg, max) = (8.710, 9.021, 9.220), stdev = 0.273
  CI (99.9%): [4.039, 14.003] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.761 ops/ms
# Warmup Iteration   2: 8.086 ops/ms
# Warmup Iteration   3: 8.326 ops/ms
Iteration   1: 8.652 ops/ms
Iteration   2: 8.757 ops/ms
Iteration   3: 8.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.574 ±(99.9%) 4.242 ops/ms [Average]
  (min, avg, max) = (8.312, 8.574, 8.757), stdev = 0.233
  CI (99.9%): [4.331, 12.816] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.507 ops/ms
# Warmup Iteration   2: 6.608 ops/ms
# Warmup Iteration   3: 7.040 ops/ms
Iteration   1: 7.321 ops/ms
Iteration   2: 7.673 ops/ms
Iteration   3: 7.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.527 ±(99.9%) 3.351 ops/ms [Average]
  (min, avg, max) = (7.321, 7.527, 7.673), stdev = 0.184
  CI (99.9%): [4.176, 10.879] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.605 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.225 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.004 ms/op
Iteration   1: 3.868 ±(99.9%) 0.011 ms/op
Iteration   2: 3.843 ±(99.9%) 0.004 ms/op
Iteration   3: 3.629 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.780 ±(99.9%) 2.401 ms/op [Average]
  (min, avg, max) = (3.629, 3.780, 3.868), stdev = 0.132
  CI (99.9%): [1.378, 6.181] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 10.558 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.008 ms/op
Iteration   1: 3.535 ±(99.9%) 0.008 ms/op
Iteration   2: 3.512 ±(99.9%) 0.012 ms/op
Iteration   3: 3.679 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.575 ±(99.9%) 1.656 ms/op [Average]
  (min, avg, max) = (3.512, 3.575, 3.679), stdev = 0.091
  CI (99.9%): [1.919, 5.231] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 12.650 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.005 ms/op
Iteration   1: 3.604 ±(99.9%) 0.010 ms/op
Iteration   2: 3.714 ±(99.9%) 0.010 ms/op
Iteration   3: 3.618 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.646 ±(99.9%) 1.087 ms/op [Average]
  (min, avg, max) = (3.604, 3.646, 3.714), stdev = 0.060
  CI (99.9%): [2.558, 4.733] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.339 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.452 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.551 ±(99.9%) 0.010 ms/op
Iteration   1: 4.577 ±(99.9%) 0.010 ms/op
Iteration   2: 4.444 ±(99.9%) 0.015 ms/op
Iteration   3: 4.457 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.493 ±(99.9%) 1.336 ms/op [Average]
  (min, avg, max) = (4.444, 4.493, 4.577), stdev = 0.073
  CI (99.9%): [3.157, 5.829] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.566 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.594 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.016 ms/op
Iteration   1: 3.964 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.397 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   7.012 ms/op
                 createUser·p0.999:  15.745 ms/op
                 createUser·p0.9999: 24.307 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   2: 3.696 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  23.265 ms/op
                 createUser·p0.9999: 27.820 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   3: 3.894 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.452 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   7.193 ms/op
                 createUser·p0.999:  28.307 ms/op
                 createUser·p0.9999: 31.902 ms/op
                 createUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 249437
  mean =      3.848 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1117 
    [ 2.500,  5.000) = 237238 
    [ 5.000,  7.500) = 9477 
    [ 7.500, 10.000) = 1008 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 52 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     22.008 ms/op
     p(99.9900) =     30.869 ms/op
     p(99.9990) =     32.146 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.682 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.011 ms/op
Iteration   1: 3.549 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.331 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.043 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  19.167 ms/op
                 existUser·p0.9999: 23.559 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   2: 3.638 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.673 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.899 ms/op
                 existUser·p0.99:   6.513 ms/op
                 existUser·p0.999:  21.867 ms/op
                 existUser·p0.9999: 24.466 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   3: 3.646 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.542 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.182 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  13.402 ms/op
                 existUser·p0.9999: 35.929 ms/op
                 existUser·p1.00:   38.797 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 265565
  mean =      3.610 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3605 
    [ 2.500,  5.000) = 251344 
    [ 5.000,  7.500) = 9055 
    [ 7.500, 10.000) = 907 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 116 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.331 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     16.830 ms/op
     p(99.9900) =     34.501 ms/op
     p(99.9990) =     37.981 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.744 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.606 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.016 ms/op
Iteration   1: 3.766 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.456 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   5.210 ms/op
                 getUser·p0.99:   7.758 ms/op
                 getUser·p0.999:  22.244 ms/op
                 getUser·p0.9999: 28.786 ms/op
                 getUser·p1.00:   29.721 ms/op

Iteration   2: 3.858 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.935 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.906 ms/op
                 getUser·p0.999:  26.298 ms/op
                 getUser·p0.9999: 36.928 ms/op
                 getUser·p1.00:   38.601 ms/op

Iteration   3: 3.683 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.470 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  9.798 ms/op
                 getUser·p0.9999: 29.590 ms/op
                 getUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 255125
  mean =      3.768 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1201 
    [ 2.500,  5.000) = 244771 
    [ 5.000,  7.500) = 7237 
    [ 7.500, 10.000) = 1229 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 93 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     21.455 ms/op
     p(99.9900) =     34.307 ms/op
     p(99.9990) =     38.040 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 13.286 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 5.236 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.610 ±(99.9%) 0.016 ms/op
Iteration   1: 4.360 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   4.202 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   8.184 ms/op
                 listUser·p0.999:  23.462 ms/op
                 listUser·p0.9999: 27.754 ms/op
                 listUser·p1.00:   32.604 ms/op

Iteration   2: 4.634 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  17.532 ms/op
                 listUser·p0.9999: 21.011 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 4.618 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   8.651 ms/op
                 listUser·p0.999:  16.286 ms/op
                 listUser·p0.9999: 18.986 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 211481
  mean =      4.534 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 186744 
    [ 5.000,  7.500) = 20613 
    [ 7.500, 10.000) = 3122 
    [10.000, 12.500) = 402 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.493 ms/op
     p(50.0000) =      4.415 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     27.160 ms/op
     p(99.9990) =     31.889 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.368 ± 5.750  ops/ms
ClientPb.existUser                       thrpt       3   9.021 ± 4.982  ops/ms
ClientPb.getUser                         thrpt       3   8.574 ± 4.242  ops/ms
ClientPb.listUser                        thrpt       3   7.527 ± 3.351  ops/ms
ClientPb.createUser                       avgt       3   3.780 ± 2.401   ms/op
ClientPb.existUser                        avgt       3   3.575 ± 1.656   ms/op
ClientPb.getUser                          avgt       3   3.646 ± 1.087   ms/op
ClientPb.listUser                         avgt       3   4.493 ± 1.336   ms/op
ClientPb.createUser                     sample  249437   3.848 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.233           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.555           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.923           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.709           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.008           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.869           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.244           ms/op
ClientPb.existUser                      sample  265565   3.610 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.331           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.510           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.096           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.678           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.830           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.501           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.797           ms/op
ClientPb.getUser                        sample  255125   3.768 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.456           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.666           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.653           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.455           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.307           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.601           ms/op
ClientPb.listUser                       sample  211481   4.534 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.493           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.480           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.416           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.160           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.604           ms/op
