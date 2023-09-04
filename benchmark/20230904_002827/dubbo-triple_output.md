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
# Warmup Iteration   1: 1.450 ops/ms
# Warmup Iteration   2: 3.651 ops/ms
# Warmup Iteration   3: 7.579 ops/ms
Iteration   1: 7.528 ops/ms
Iteration   2: 8.160 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.964 ±(99.9%) 6.896 ops/ms [Average]
  (min, avg, max) = (7.528, 7.964, 8.203), stdev = 0.378
  CI (99.9%): [1.067, 14.860] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.244 ops/ms
# Warmup Iteration   2: 7.417 ops/ms
# Warmup Iteration   3: 8.090 ops/ms
Iteration   1: 8.305 ops/ms
Iteration   2: 8.437 ops/ms
Iteration   3: 8.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.384 ±(99.9%) 1.276 ops/ms [Average]
  (min, avg, max) = (8.305, 8.384, 8.437), stdev = 0.070
  CI (99.9%): [7.108, 9.660] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.081 ops/ms
# Warmup Iteration   2: 6.385 ops/ms
# Warmup Iteration   3: 7.670 ops/ms
Iteration   1: 7.912 ops/ms
Iteration   2: 7.451 ops/ms
Iteration   3: 7.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.756 ±(99.9%) 4.812 ops/ms [Average]
  (min, avg, max) = (7.451, 7.756, 7.912), stdev = 0.264
  CI (99.9%): [2.944, 12.568] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.924 ops/ms
# Warmup Iteration   2: 5.429 ops/ms
# Warmup Iteration   3: 6.876 ops/ms
Iteration   1: 6.847 ops/ms
Iteration   2: 7.005 ops/ms
Iteration   3: 6.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.940 ±(99.9%) 1.505 ops/ms [Average]
  (min, avg, max) = (6.847, 6.940, 7.005), stdev = 0.082
  CI (99.9%): [5.435, 8.445] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.558 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.597 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.009 ms/op
Iteration   1: 3.954 ±(99.9%) 0.010 ms/op
Iteration   2: 4.076 ±(99.9%) 0.006 ms/op
Iteration   3: 4.091 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.041 ±(99.9%) 1.371 ms/op [Average]
  (min, avg, max) = (3.954, 4.041, 4.091), stdev = 0.075
  CI (99.9%): [2.669, 5.412] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.507 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.005 ms/op
Iteration   1: 3.886 ±(99.9%) 0.007 ms/op
Iteration   2: 3.852 ±(99.9%) 0.004 ms/op
Iteration   3: 3.774 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.837 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (3.774, 3.837, 3.886), stdev = 0.058
  CI (99.9%): [2.786, 4.889] (assumes normal distribution)


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
# Warmup Iteration   1: 12.112 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.970 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.005 ms/op
Iteration   1: 3.915 ±(99.9%) 0.008 ms/op
Iteration   2: 4.096 ±(99.9%) 0.006 ms/op
Iteration   3: 3.942 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.984 ±(99.9%) 1.781 ms/op [Average]
  (min, avg, max) = (3.915, 3.984, 4.096), stdev = 0.098
  CI (99.9%): [2.203, 5.765] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 12.958 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.435 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.904 ±(99.9%) 0.008 ms/op
Iteration   1: 4.652 ±(99.9%) 0.007 ms/op
Iteration   2: 4.651 ±(99.9%) 0.011 ms/op
Iteration   3: 4.564 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.622 ±(99.9%) 0.923 ms/op [Average]
  (min, avg, max) = (4.564, 4.622, 4.652), stdev = 0.051
  CI (99.9%): [3.699, 5.545] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.749 ±(99.9%) 0.163 ms/op
# Warmup Iteration   2: 5.240 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.541 ±(99.9%) 0.023 ms/op
Iteration   1: 4.008 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.837 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.489 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  11.207 ms/op
                 createUser·p0.9999: 25.759 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   2: 3.938 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.286 ms/op
                 createUser·p0.50:   3.781 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   7.864 ms/op
                 createUser·p0.999:  24.759 ms/op
                 createUser·p0.9999: 27.816 ms/op
                 createUser·p1.00:   29.426 ms/op

Iteration   3: 3.960 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.421 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   7.704 ms/op
                 createUser·p0.999:  27.427 ms/op
                 createUser·p0.9999: 42.467 ms/op
                 createUser·p1.00:   42.795 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241824
  mean =      3.968 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 229247 
    [ 5.000, 10.000) = 11743 
    [10.000, 15.000) = 525 
    [15.000, 20.000) = 30 
    [20.000, 25.000) = 80 
    [25.000, 30.000) = 142 
    [30.000, 35.000) = 25 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     23.724 ms/op
     p(99.9900) =     38.499 ms/op
     p(99.9990) =     42.664 ms/op
     p(99.9999) =     42.795 ms/op
    p(100.0000) =     42.795 ms/op


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
# Warmup Iteration   1: 11.293 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 4.163 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.012 ms/op
Iteration   1: 3.945 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.626 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   6.300 ms/op
                 existUser·p0.99:   8.602 ms/op
                 existUser·p0.999:  17.072 ms/op
                 existUser·p0.9999: 26.765 ms/op
                 existUser·p1.00:   28.017 ms/op

Iteration   2: 3.768 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.839 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   7.234 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 28.297 ms/op
                 existUser·p1.00:   29.164 ms/op

Iteration   3: 3.824 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.929 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.850 ms/op
                 existUser·p0.99:   6.801 ms/op
                 existUser·p0.999:  27.984 ms/op
                 existUser·p0.9999: 37.851 ms/op
                 existUser·p1.00:   38.339 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249589
  mean =      3.845 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1350 
    [ 2.500,  5.000) = 235147 
    [ 5.000,  7.500) = 9750 
    [ 7.500, 10.000) = 2483 
    [10.000, 12.500) = 483 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.626 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     16.864 ms/op
     p(99.9900) =     35.728 ms/op
     p(99.9990) =     38.273 ms/op
     p(99.9999) =     38.339 ms/op
    p(100.0000) =     38.339 ms/op


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
# Warmup Iteration   1: 12.768 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 4.537 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.013 ms/op
Iteration   1: 3.876 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   7.688 ms/op
                 getUser·p0.999:  22.494 ms/op
                 getUser·p0.9999: 24.969 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.981 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.726 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.997 ms/op
                 getUser·p0.99:   7.586 ms/op
                 getUser·p0.999:  14.385 ms/op
                 getUser·p0.9999: 26.965 ms/op
                 getUser·p1.00:   28.180 ms/op

Iteration   3: 3.973 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.825 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   7.299 ms/op
                 getUser·p0.999:  29.658 ms/op
                 getUser·p0.9999: 37.156 ms/op
                 getUser·p1.00:   37.880 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 243328
  mean =      3.943 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 268 
    [ 2.500,  5.000) = 231397 
    [ 5.000,  7.500) = 9038 
    [ 7.500, 10.000) = 1828 
    [10.000, 12.500) = 393 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.618 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     22.479 ms/op
     p(99.9900) =     35.805 ms/op
     p(99.9990) =     37.786 ms/op
     p(99.9999) =     37.880 ms/op
    p(100.0000) =     37.880 ms/op


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
# Warmup Iteration   1: 13.931 ±(99.9%) 0.208 ms/op
# Warmup Iteration   2: 5.608 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.999 ±(99.9%) 0.020 ms/op
Iteration   1: 4.790 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.490 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   10.355 ms/op
                 listUser·p0.999:  26.771 ms/op
                 listUser·p0.9999: 28.978 ms/op
                 listUser·p1.00:   30.081 ms/op

Iteration   2: 4.790 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.342 ms/op
                 listUser·p0.99:   9.650 ms/op
                 listUser·p0.999:  25.068 ms/op
                 listUser·p0.9999: 29.480 ms/op
                 listUser·p1.00:   30.015 ms/op

Iteration   3: 4.634 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.462 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  16.136 ms/op
                 listUser·p0.9999: 21.466 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202579
  mean =      4.737 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 169358 
    [ 5.000,  7.500) = 26815 
    [ 7.500, 10.000) = 4473 
    [10.000, 12.500) = 1178 
    [12.500, 15.000) = 367 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 117 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.204 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      6.078 ms/op
     p(99.0000) =      9.863 ms/op
     p(99.9000) =     23.626 ms/op
     p(99.9900) =     28.991 ms/op
     p(99.9990) =     30.012 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.964 ± 6.896  ops/ms
ClientPb.existUser                       thrpt       3   8.384 ± 1.276  ops/ms
ClientPb.getUser                         thrpt       3   7.756 ± 4.812  ops/ms
ClientPb.listUser                        thrpt       3   6.940 ± 1.505  ops/ms
ClientPb.createUser                       avgt       3   4.041 ± 1.371   ms/op
ClientPb.existUser                        avgt       3   3.837 ± 1.052   ms/op
ClientPb.getUser                          avgt       3   3.984 ± 1.781   ms/op
ClientPb.listUser                         avgt       3   4.622 ± 0.923   ms/op
ClientPb.createUser                     sample  241824   3.968 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.286           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.522           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.046           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.528           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.724           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.499           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.795           ms/op
ClientPb.existUser                      sample  249589   3.845 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.626           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.046           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.930           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.864           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.728           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.339           ms/op
ClientPb.getUser                        sample  243328   3.943 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.618           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.440           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.940           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.569           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.479           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.805           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.880           ms/op
ClientPb.listUser                       sample  202579   4.737 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.204           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.218           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.078           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.863           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.626           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.991           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.081           ms/op
