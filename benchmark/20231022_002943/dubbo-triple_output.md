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
# Warmup Iteration   1: 1.478 ops/ms
# Warmup Iteration   2: 3.325 ops/ms
# Warmup Iteration   3: 6.863 ops/ms
Iteration   1: 7.418 ops/ms
Iteration   2: 8.029 ops/ms
Iteration   3: 7.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.713 ±(99.9%) 5.583 ops/ms [Average]
  (min, avg, max) = (7.418, 7.713, 8.029), stdev = 0.306
  CI (99.9%): [2.131, 13.296] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.105 ops/ms
# Warmup Iteration   2: 6.011 ops/ms
# Warmup Iteration   3: 7.936 ops/ms
Iteration   1: 8.132 ops/ms
Iteration   2: 8.106 ops/ms
Iteration   3: 8.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.223 ±(99.9%) 3.280 ops/ms [Average]
  (min, avg, max) = (8.106, 8.223, 8.430), stdev = 0.180
  CI (99.9%): [4.943, 11.503] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.957 ops/ms
# Warmup Iteration   2: 6.593 ops/ms
# Warmup Iteration   3: 7.470 ops/ms
Iteration   1: 7.723 ops/ms
Iteration   2: 7.759 ops/ms
Iteration   3: 7.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.797 ±(99.9%) 1.814 ops/ms [Average]
  (min, avg, max) = (7.723, 7.797, 7.910), stdev = 0.099
  CI (99.9%): [5.984, 9.611] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.967 ops/ms
# Warmup Iteration   2: 5.323 ops/ms
# Warmup Iteration   3: 6.387 ops/ms
Iteration   1: 6.273 ops/ms
Iteration   2: 6.345 ops/ms
Iteration   3: 6.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.438 ±(99.9%) 4.113 ops/ms [Average]
  (min, avg, max) = (6.273, 6.438, 6.695), stdev = 0.225
  CI (99.9%): [2.325, 10.551] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 14.730 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 5.934 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.498 ±(99.9%) 0.004 ms/op
Iteration   1: 3.953 ±(99.9%) 0.007 ms/op
Iteration   2: 4.000 ±(99.9%) 0.004 ms/op
Iteration   3: 4.153 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.035 ±(99.9%) 1.911 ms/op [Average]
  (min, avg, max) = (3.953, 4.035, 4.153), stdev = 0.105
  CI (99.9%): [2.124, 5.947] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 12.978 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.225 ±(99.9%) 0.006 ms/op
Iteration   1: 4.027 ±(99.9%) 0.003 ms/op
Iteration   2: 4.189 ±(99.9%) 0.005 ms/op
Iteration   3: 4.189 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.135 ±(99.9%) 1.706 ms/op [Average]
  (min, avg, max) = (4.027, 4.135, 4.189), stdev = 0.094
  CI (99.9%): [2.429, 5.841] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 15.030 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.799 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.005 ms/op
Iteration   1: 4.199 ±(99.9%) 0.005 ms/op
Iteration   2: 4.155 ±(99.9%) 0.006 ms/op
Iteration   3: 4.040 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.131 ±(99.9%) 1.497 ms/op [Average]
  (min, avg, max) = (4.040, 4.131, 4.199), stdev = 0.082
  CI (99.9%): [2.634, 5.628] (assumes normal distribution)


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
# Warmup Iteration   1: 16.764 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.019 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.044 ±(99.9%) 0.007 ms/op
Iteration   1: 4.992 ±(99.9%) 0.007 ms/op
Iteration   2: 4.865 ±(99.9%) 0.008 ms/op
Iteration   3: 4.917 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.925 ±(99.9%) 1.163 ms/op [Average]
  (min, avg, max) = (4.865, 4.925, 4.992), stdev = 0.064
  CI (99.9%): [3.762, 6.088] (assumes normal distribution)


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
# Warmup Iteration   1: 12.601 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 5.190 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.543 ±(99.9%) 0.020 ms/op
Iteration   1: 4.118 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.491 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   8.538 ms/op
                 createUser·p0.999:  13.815 ms/op
                 createUser·p0.9999: 26.924 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   2: 4.083 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   7.660 ms/op
                 createUser·p0.999:  26.149 ms/op
                 createUser·p0.9999: 28.630 ms/op
                 createUser·p1.00:   29.983 ms/op

Iteration   3: 4.080 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.622 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   7.593 ms/op
                 createUser·p0.999:  28.459 ms/op
                 createUser·p0.9999: 30.769 ms/op
                 createUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234727
  mean =      4.093 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 239 
    [ 2.500,  5.000) = 219311 
    [ 5.000,  7.500) = 11764 
    [ 7.500, 10.000) = 2307 
    [10.000, 12.500) = 631 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 119 
    [27.500, 30.000) = 103 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     25.109 ms/op
     p(99.9900) =     29.607 ms/op
     p(99.9990) =     32.091 ms/op
     p(99.9999) =     32.670 ms/op
    p(100.0000) =     32.670 ms/op


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
# Warmup Iteration   1: 11.867 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.014 ms/op
Iteration   1: 4.127 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.671 ms/op
                 existUser·p0.50:   3.949 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   5.652 ms/op
                 existUser·p0.99:   8.069 ms/op
                 existUser·p0.999:  12.071 ms/op
                 existUser·p0.9999: 27.869 ms/op
                 existUser·p1.00:   28.574 ms/op

Iteration   2: 4.051 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.634 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   5.431 ms/op
                 existUser·p0.99:   8.782 ms/op
                 existUser·p0.999:  25.597 ms/op
                 existUser·p0.9999: 27.591 ms/op
                 existUser·p1.00:   29.196 ms/op

Iteration   3: 4.111 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.214 ms/op
                 existUser·p0.50:   3.928 ms/op
                 existUser·p0.90:   4.743 ms/op
                 existUser·p0.95:   5.642 ms/op
                 existUser·p0.99:   8.061 ms/op
                 existUser·p0.999:  13.094 ms/op
                 existUser·p0.9999: 34.945 ms/op
                 existUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 234345
  mean =      4.096 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 197 
    [ 2.500,  5.000) = 215438 
    [ 5.000,  7.500) = 15260 
    [ 7.500, 10.000) = 2443 
    [10.000, 12.500) = 611 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 36 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      8.225 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     34.210 ms/op
     p(99.9990) =     35.105 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 12.472 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.766 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.014 ms/op
Iteration   1: 4.280 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   6.570 ms/op
                 getUser·p0.99:   9.716 ms/op
                 getUser·p0.999:  20.451 ms/op
                 getUser·p0.9999: 25.494 ms/op
                 getUser·p1.00:   27.099 ms/op

Iteration   2: 4.076 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   3.871 ms/op
                 getUser·p0.90:   4.727 ms/op
                 getUser·p0.95:   5.153 ms/op
                 getUser·p0.99:   7.651 ms/op
                 getUser·p0.999:  10.608 ms/op
                 getUser·p0.9999: 27.965 ms/op
                 getUser·p1.00:   28.672 ms/op

Iteration   3: 4.061 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.187 ms/op
                 getUser·p0.50:   3.940 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   7.012 ms/op
                 getUser·p0.999:  27.093 ms/op
                 getUser·p0.9999: 31.187 ms/op
                 getUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232030
  mean =      4.137 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 215676 
    [ 5.000,  7.500) = 12502 
    [ 7.500, 10.000) = 2768 
    [10.000, 12.500) = 546 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     21.262 ms/op
     p(99.9900) =     29.917 ms/op
     p(99.9990) =     32.016 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.993 ±(99.9%) 0.238 ms/op
# Warmup Iteration   2: 6.079 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.180 ±(99.9%) 0.021 ms/op
Iteration   1: 5.023 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.995 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   6.963 ms/op
                 listUser·p0.99:   9.814 ms/op
                 listUser·p0.999:  25.526 ms/op
                 listUser·p0.9999: 26.739 ms/op
                 listUser·p1.00:   28.639 ms/op

Iteration   2: 4.847 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.700 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.382 ms/op
                 listUser·p0.95:   6.193 ms/op
                 listUser·p0.99:   9.265 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 25.988 ms/op
                 listUser·p1.00:   26.870 ms/op

Iteration   3: 5.103 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   7.168 ms/op
                 listUser·p0.99:   9.961 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 25.769 ms/op
                 listUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192364
  mean =      4.989 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 131932 
    [ 5.000,  7.500) = 53595 
    [ 7.500, 10.000) = 5162 
    [10.000, 12.500) = 851 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 110 

  Percentiles, ms/op:
      p(0.0000) =      1.700 ms/op
     p(50.0000) =      4.694 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.816 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     23.462 ms/op
     p(99.9900) =     26.542 ms/op
     p(99.9990) =     28.306 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.713 ± 5.583  ops/ms
ClientPb.existUser                       thrpt       3   8.223 ± 3.280  ops/ms
ClientPb.getUser                         thrpt       3   7.797 ± 1.814  ops/ms
ClientPb.listUser                        thrpt       3   6.438 ± 4.113  ops/ms
ClientPb.createUser                       avgt       3   4.035 ± 1.911   ms/op
ClientPb.existUser                        avgt       3   4.135 ± 1.706   ms/op
ClientPb.getUser                          avgt       3   4.131 ± 1.497   ms/op
ClientPb.listUser                         avgt       3   4.925 ± 1.163   ms/op
ClientPb.createUser                     sample  234727   4.093 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.491           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.686           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.218           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.143           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.109           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.607           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.670           ms/op
ClientPb.existUser                      sample  234345   4.096 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.214           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.595           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.225           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.237           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.210           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.914           ms/op
ClientPb.getUser                        sample  232030   4.137 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.083           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.472           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.315           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.262           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.917           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.113           ms/op
ClientPb.listUser                       sample  192364   4.989 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.700           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.816           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.683           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.462           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.542           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.639           ms/op
