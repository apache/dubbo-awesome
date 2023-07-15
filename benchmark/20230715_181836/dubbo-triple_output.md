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
# Warmup Iteration   1: 1.789 ops/ms
# Warmup Iteration   2: 4.174 ops/ms
# Warmup Iteration   3: 7.653 ops/ms
Iteration   1: 7.953 ops/ms
Iteration   2: 8.132 ops/ms
Iteration   3: 8.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.159 ±(99.9%) 4.020 ops/ms [Average]
  (min, avg, max) = (7.953, 8.159, 8.392), stdev = 0.220
  CI (99.9%): [4.139, 12.179] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.619 ops/ms
# Warmup Iteration   2: 7.461 ops/ms
# Warmup Iteration   3: 8.442 ops/ms
Iteration   1: 8.832 ops/ms
Iteration   2: 8.648 ops/ms
Iteration   3: 8.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.815 ±(99.9%) 2.907 ops/ms [Average]
  (min, avg, max) = (8.648, 8.815, 8.965), stdev = 0.159
  CI (99.9%): [5.908, 11.721] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.370 ops/ms
# Warmup Iteration   2: 6.673 ops/ms
# Warmup Iteration   3: 8.059 ops/ms
Iteration   1: 8.229 ops/ms
Iteration   2: 8.205 ops/ms
Iteration   3: 8.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.347 ±(99.9%) 4.117 ops/ms [Average]
  (min, avg, max) = (8.205, 8.347, 8.608), stdev = 0.226
  CI (99.9%): [4.230, 12.465] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.282 ops/ms
# Warmup Iteration   2: 6.147 ops/ms
# Warmup Iteration   3: 7.001 ops/ms
Iteration   1: 7.197 ops/ms
Iteration   2: 6.918 ops/ms
Iteration   3: 6.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.955 ±(99.9%) 4.129 ops/ms [Average]
  (min, avg, max) = (6.749, 6.955, 7.197), stdev = 0.226
  CI (99.9%): [2.826, 11.084] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.165 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.008 ms/op
Iteration   1: 3.728 ±(99.9%) 0.009 ms/op
Iteration   2: 3.746 ±(99.9%) 0.004 ms/op
Iteration   3: 3.697 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.724 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (3.697, 3.724, 3.746), stdev = 0.025
  CI (99.9%): [3.266, 4.181] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.868 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.722 ±(99.9%) 0.007 ms/op
Iteration   1: 3.650 ±(99.9%) 0.009 ms/op
Iteration   2: 3.550 ±(99.9%) 0.010 ms/op
Iteration   3: 3.592 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.597 ±(99.9%) 0.911 ms/op [Average]
  (min, avg, max) = (3.550, 3.597, 3.650), stdev = 0.050
  CI (99.9%): [2.686, 4.509] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.248 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.006 ms/op
Iteration   1: 3.695 ±(99.9%) 0.014 ms/op
Iteration   2: 3.831 ±(99.9%) 0.006 ms/op
Iteration   3: 3.696 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.740 ±(99.9%) 1.425 ms/op [Average]
  (min, avg, max) = (3.695, 3.740, 3.831), stdev = 0.078
  CI (99.9%): [2.315, 5.166] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.204 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.716 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.600 ±(99.9%) 0.013 ms/op
Iteration   1: 4.484 ±(99.9%) 0.010 ms/op
Iteration   2: 4.351 ±(99.9%) 0.014 ms/op
Iteration   3: 4.433 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.422 ±(99.9%) 1.220 ms/op [Average]
  (min, avg, max) = (4.351, 4.422, 4.484), stdev = 0.067
  CI (99.9%): [3.202, 5.643] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 11.340 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.584 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.014 ms/op
Iteration   1: 3.680 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.825 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  17.890 ms/op
                 createUser·p0.9999: 24.710 ms/op
                 createUser·p1.00:   25.362 ms/op

Iteration   2: 3.763 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.309 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.513 ms/op
                 createUser·p0.999:  9.466 ms/op
                 createUser·p0.9999: 22.888 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 3.757 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.610 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   6.906 ms/op
                 createUser·p0.999:  23.462 ms/op
                 createUser·p0.9999: 26.132 ms/op
                 createUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 257171
  mean =      3.733 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 975 
    [ 2.500,  5.000) = 244157 
    [ 5.000,  7.500) = 10610 
    [ 7.500, 10.000) = 936 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     18.514 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     27.343 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.576 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.822 ±(99.9%) 0.012 ms/op
Iteration   1: 3.640 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.634 ms/op
                 existUser·p0.50:   3.547 ms/op
                 existUser·p0.90:   4.100 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  11.207 ms/op
                 existUser·p0.9999: 24.452 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   2: 3.703 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.637 ms/op
                 existUser·p0.90:   4.129 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   6.889 ms/op
                 existUser·p0.999:  13.095 ms/op
                 existUser·p0.9999: 25.890 ms/op
                 existUser·p1.00:   28.541 ms/op

Iteration   3: 3.592 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.411 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  26.372 ms/op
                 existUser·p0.9999: 31.099 ms/op
                 existUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 263350
  mean =      3.644 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3063 
    [ 2.500,  5.000) = 252361 
    [ 5.000,  7.500) = 6703 
    [ 7.500, 10.000) = 769 
    [10.000, 12.500) = 164 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.386 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.480 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     30.103 ms/op
     p(99.9990) =     31.895 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.530 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.350 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.015 ms/op
Iteration   1: 3.771 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.849 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.710 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  17.727 ms/op
                 getUser·p0.9999: 23.888 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 3.762 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  24.052 ms/op
                 getUser·p0.9999: 31.014 ms/op
                 getUser·p1.00:   32.440 ms/op

Iteration   3: 3.749 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   3.654 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  24.711 ms/op
                 getUser·p0.9999: 34.106 ms/op
                 getUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 255306
  mean =      3.761 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1007 
    [ 2.500,  5.000) = 244662 
    [ 5.000,  7.500) = 8392 
    [ 7.500, 10.000) = 759 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     20.951 ms/op
     p(99.9900) =     32.698 ms/op
     p(99.9990) =     35.062 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.826 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 5.560 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.577 ±(99.9%) 0.015 ms/op
Iteration   1: 4.557 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   8.441 ms/op
                 listUser·p0.999:  24.698 ms/op
                 listUser·p0.9999: 26.867 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   2: 4.595 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  18.757 ms/op
                 listUser·p0.9999: 26.870 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   3: 4.647 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.710 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.107 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  16.306 ms/op
                 listUser·p0.9999: 20.189 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208618
  mean =      4.600 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 178923 
    [ 5.000,  7.500) = 24683 
    [ 7.500, 10.000) = 3932 
    [10.000, 12.500) = 538 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      1.548 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.775 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     18.940 ms/op
     p(99.9900) =     26.416 ms/op
     p(99.9990) =     27.497 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.159 ± 4.020  ops/ms
ClientPb.existUser                       thrpt       3   8.815 ± 2.907  ops/ms
ClientPb.getUser                         thrpt       3   8.347 ± 4.117  ops/ms
ClientPb.listUser                        thrpt       3   6.955 ± 4.129  ops/ms
ClientPb.createUser                       avgt       3   3.724 ± 0.457   ms/op
ClientPb.existUser                        avgt       3   3.597 ± 0.911   ms/op
ClientPb.getUser                          avgt       3   3.740 ± 1.425   ms/op
ClientPb.listUser                         avgt       3   4.422 ± 1.220   ms/op
ClientPb.createUser                     sample  257171   3.733 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.309           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.584           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.923           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.514           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.199           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.525           ms/op
ClientPb.existUser                      sample  263350   3.644 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.386           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.599           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.103           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.178           ms/op
ClientPb.getUser                        sample  255306   3.761 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.632           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.293           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.686           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.578           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.951           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.698           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.127           ms/op
ClientPb.listUser                       sample  208618   4.600 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.548           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.186           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.775           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.940           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.416           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.525           ms/op
