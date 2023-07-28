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
# Warmup Iteration   1: 1.595 ops/ms
# Warmup Iteration   2: 3.712 ops/ms
# Warmup Iteration   3: 7.401 ops/ms
Iteration   1: 7.092 ops/ms
Iteration   2: 7.850 ops/ms
Iteration   3: 7.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.637 ±(99.9%) 8.681 ops/ms [Average]
  (min, avg, max) = (7.092, 7.637, 7.968), stdev = 0.476
  CI (99.9%): [≈ 0, 16.317] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.221 ops/ms
# Warmup Iteration   2: 6.577 ops/ms
# Warmup Iteration   3: 7.831 ops/ms
Iteration   1: 8.355 ops/ms
Iteration   2: 8.320 ops/ms
Iteration   3: 8.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.241 ±(99.9%) 3.077 ops/ms [Average]
  (min, avg, max) = (8.047, 8.241, 8.355), stdev = 0.169
  CI (99.9%): [5.164, 11.318] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.204 ops/ms
# Warmup Iteration   2: 5.966 ops/ms
# Warmup Iteration   3: 7.587 ops/ms
Iteration   1: 7.948 ops/ms
Iteration   2: 7.727 ops/ms
Iteration   3: 8.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.029 ±(99.9%) 6.386 ops/ms [Average]
  (min, avg, max) = (7.727, 8.029, 8.413), stdev = 0.350
  CI (99.9%): [1.644, 14.415] (assumes normal distribution)


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
# Warmup Iteration   1: 2.055 ops/ms
# Warmup Iteration   2: 5.698 ops/ms
# Warmup Iteration   3: 6.525 ops/ms
Iteration   1: 6.719 ops/ms
Iteration   2: 7.013 ops/ms
Iteration   3: 6.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.902 ±(99.9%) 2.913 ops/ms [Average]
  (min, avg, max) = (6.719, 6.902, 7.013), stdev = 0.160
  CI (99.9%): [3.989, 9.816] (assumes normal distribution)


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
# Warmup Iteration   1: 13.176 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.748 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.235 ±(99.9%) 0.004 ms/op
Iteration   1: 3.931 ±(99.9%) 0.005 ms/op
Iteration   2: 4.009 ±(99.9%) 0.008 ms/op
Iteration   3: 3.867 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.936 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (3.867, 3.936, 4.009), stdev = 0.071
  CI (99.9%): [2.640, 5.232] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.973 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.447 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.006 ms/op
Iteration   1: 3.722 ±(99.9%) 0.010 ms/op
Iteration   2: 3.768 ±(99.9%) 0.011 ms/op
Iteration   3: 3.813 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.767 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (3.722, 3.767, 3.813), stdev = 0.045
  CI (99.9%): [2.941, 4.594] (assumes normal distribution)


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
# Warmup Iteration   1: 13.266 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.496 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.005 ms/op
Iteration   1: 3.981 ±(99.9%) 0.006 ms/op
Iteration   2: 3.852 ±(99.9%) 0.008 ms/op
Iteration   3: 4.064 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.966 ±(99.9%) 1.950 ms/op [Average]
  (min, avg, max) = (3.852, 3.966, 4.064), stdev = 0.107
  CI (99.9%): [2.016, 5.916] (assumes normal distribution)


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
# Warmup Iteration   1: 14.146 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.427 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.626 ±(99.9%) 0.012 ms/op
Iteration   1: 4.758 ±(99.9%) 0.011 ms/op
Iteration   2: 4.589 ±(99.9%) 0.011 ms/op
Iteration   3: 4.530 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.626 ±(99.9%) 2.160 ms/op [Average]
  (min, avg, max) = (4.530, 4.626, 4.758), stdev = 0.118
  CI (99.9%): [2.466, 6.786] (assumes normal distribution)


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
# Warmup Iteration   1: 11.933 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.878 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.701 ±(99.9%) 0.020 ms/op
Iteration   1: 3.961 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.683 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   7.332 ms/op
                 createUser·p0.999:  23.530 ms/op
                 createUser·p0.9999: 25.851 ms/op
                 createUser·p1.00:   27.099 ms/op

Iteration   2: 4.119 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.815 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   7.345 ms/op
                 createUser·p0.999:  11.737 ms/op
                 createUser·p0.9999: 27.861 ms/op
                 createUser·p1.00:   28.606 ms/op

Iteration   3: 3.996 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.978 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  29.064 ms/op
                 createUser·p0.9999: 35.914 ms/op
                 createUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238469
  mean =      4.024 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 165 
    [ 2.500,  5.000) = 222931 
    [ 5.000,  7.500) = 13570 
    [ 7.500, 10.000) = 1221 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.683 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.358 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     23.726 ms/op
     p(99.9900) =     33.696 ms/op
     p(99.9990) =     36.191 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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
# Warmup Iteration   1: 11.693 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.012 ms/op
Iteration   1: 3.850 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.818 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   7.102 ms/op
                 existUser·p0.999:  11.944 ms/op
                 existUser·p0.9999: 33.045 ms/op
                 existUser·p1.00:   33.456 ms/op

Iteration   2: 4.048 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.739 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.734 ms/op
                 existUser·p0.99:   7.807 ms/op
                 existUser·p0.999:  12.648 ms/op
                 existUser·p0.9999: 29.757 ms/op
                 existUser·p1.00:   30.179 ms/op

Iteration   3: 3.970 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.464 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   5.218 ms/op
                 existUser·p0.99:   7.496 ms/op
                 existUser·p0.999:  27.010 ms/op
                 existUser·p0.9999: 31.396 ms/op
                 existUser·p1.00:   31.916 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242745
  mean =      3.954 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 402 
    [ 2.500,  5.000) = 226276 
    [ 5.000,  7.500) = 13696 
    [ 7.500, 10.000) = 1592 
    [10.000, 12.500) = 417 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 106 
    [30.000, 32.500) = 73 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     19.243 ms/op
     p(99.9900) =     31.940 ms/op
     p(99.9990) =     33.377 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 12.676 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.629 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.203 ±(99.9%) 0.012 ms/op
Iteration   1: 4.121 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.870 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   7.799 ms/op
                 getUser·p0.999:  15.815 ms/op
                 getUser·p0.9999: 26.190 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   2: 3.869 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  25.002 ms/op
                 getUser·p0.9999: 32.010 ms/op
                 getUser·p1.00:   37.421 ms/op

Iteration   3: 3.977 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.093 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   7.119 ms/op
                 getUser·p0.999:  11.922 ms/op
                 getUser·p0.9999: 32.207 ms/op
                 getUser·p1.00:   32.670 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240567
  mean =      3.987 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 229429 
    [ 5.000,  7.500) = 8919 
    [ 7.500, 10.000) = 1378 
    [10.000, 12.500) = 432 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 91 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 33 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.612 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     15.815 ms/op
     p(99.9900) =     30.831 ms/op
     p(99.9990) =     34.259 ms/op
     p(99.9999) =     37.421 ms/op
    p(100.0000) =     37.421 ms/op


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
# Warmup Iteration   1: 15.715 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 6.161 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.846 ±(99.9%) 0.017 ms/op
Iteration   1: 4.707 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.810 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  22.544 ms/op
                 listUser·p0.9999: 24.865 ms/op
                 listUser·p1.00:   26.575 ms/op

Iteration   2: 4.836 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.208 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.341 ms/op
                 listUser·p0.99:   10.043 ms/op
                 listUser·p0.999:  23.763 ms/op
                 listUser·p0.9999: 29.766 ms/op
                 listUser·p1.00:   30.310 ms/op

Iteration   3: 4.699 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.712 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  16.612 ms/op
                 listUser·p0.9999: 18.809 ms/op
                 listUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 202232
  mean =      4.746 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 169619 
    [ 5.000,  7.500) = 27093 
    [ 7.500, 10.000) = 4100 
    [10.000, 12.500) = 750 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.810 ms/op
     p(50.0000) =      4.514 ms/op
     p(90.0000) =      5.251 ms/op
     p(95.0000) =      5.917 ms/op
     p(99.0000) =      9.126 ms/op
     p(99.9000) =     20.137 ms/op
     p(99.9900) =     28.093 ms/op
     p(99.9990) =     30.113 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.637 ± 8.681  ops/ms
ClientPb.existUser                       thrpt       3   8.241 ± 3.077  ops/ms
ClientPb.getUser                         thrpt       3   8.029 ± 6.386  ops/ms
ClientPb.listUser                        thrpt       3   6.902 ± 2.913  ops/ms
ClientPb.createUser                       avgt       3   3.936 ± 1.296   ms/op
ClientPb.existUser                        avgt       3   3.767 ± 0.826   ms/op
ClientPb.getUser                          avgt       3   3.966 ± 1.950   ms/op
ClientPb.listUser                         avgt       3   4.626 ± 2.160   ms/op
ClientPb.createUser                     sample  238469   4.024 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.683           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.358           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.086           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.726           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.696           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.241           ms/op
ClientPb.existUser                      sample  242745   3.954 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.818           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.447           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.243           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.940           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.456           ms/op
ClientPb.getUser                        sample  240567   3.987 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.612           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.324           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.815           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.831           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.421           ms/op
ClientPb.listUser                       sample  202232   4.746 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.810           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.251           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.917           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.126           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.137           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.093           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.310           ms/op
