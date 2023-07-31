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
# Warmup Iteration   1: 1.647 ops/ms
# Warmup Iteration   2: 3.785 ops/ms
# Warmup Iteration   3: 7.182 ops/ms
Iteration   1: 7.609 ops/ms
Iteration   2: 8.044 ops/ms
Iteration   3: 8.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.005 ±(99.9%) 6.891 ops/ms [Average]
  (min, avg, max) = (7.609, 8.005, 8.361), stdev = 0.378
  CI (99.9%): [1.114, 14.895] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.551 ops/ms
# Warmup Iteration   2: 7.461 ops/ms
# Warmup Iteration   3: 8.585 ops/ms
Iteration   1: 8.424 ops/ms
Iteration   2: 8.641 ops/ms
Iteration   3: 8.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.560 ±(99.9%) 2.164 ops/ms [Average]
  (min, avg, max) = (8.424, 8.560, 8.641), stdev = 0.119
  CI (99.9%): [6.396, 10.724] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.210 ops/ms
# Warmup Iteration   2: 7.014 ops/ms
# Warmup Iteration   3: 8.177 ops/ms
Iteration   1: 8.571 ops/ms
Iteration   2: 8.362 ops/ms
Iteration   3: 8.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.401 ±(99.9%) 2.816 ops/ms [Average]
  (min, avg, max) = (8.270, 8.401, 8.571), stdev = 0.154
  CI (99.9%): [5.585, 11.217] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.999 ops/ms
# Warmup Iteration   2: 5.587 ops/ms
# Warmup Iteration   3: 6.933 ops/ms
Iteration   1: 6.977 ops/ms
Iteration   2: 6.836 ops/ms
Iteration   3: 6.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.898 ±(99.9%) 1.312 ops/ms [Average]
  (min, avg, max) = (6.836, 6.898, 6.977), stdev = 0.072
  CI (99.9%): [5.586, 8.210] (assumes normal distribution)


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
# Warmup Iteration   1: 12.783 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.736 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.005 ms/op
Iteration   1: 3.901 ±(99.9%) 0.008 ms/op
Iteration   2: 3.846 ±(99.9%) 0.004 ms/op
Iteration   3: 3.711 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.819 ±(99.9%) 1.785 ms/op [Average]
  (min, avg, max) = (3.711, 3.819, 3.901), stdev = 0.098
  CI (99.9%): [2.034, 5.604] (assumes normal distribution)


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
# Warmup Iteration   1: 12.747 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.744 ±(99.9%) 0.003 ms/op
Iteration   1: 3.682 ±(99.9%) 0.012 ms/op
Iteration   2: 3.736 ±(99.9%) 0.011 ms/op
Iteration   3: 3.767 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.728 ±(99.9%) 0.783 ms/op [Average]
  (min, avg, max) = (3.682, 3.728, 3.767), stdev = 0.043
  CI (99.9%): [2.945, 4.512] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.110 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.685 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.151 ±(99.9%) 0.007 ms/op
Iteration   1: 4.142 ±(99.9%) 0.007 ms/op
Iteration   2: 3.863 ±(99.9%) 0.006 ms/op
Iteration   3: 3.862 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.955 ±(99.9%) 2.944 ms/op [Average]
  (min, avg, max) = (3.862, 3.955, 4.142), stdev = 0.161
  CI (99.9%): [1.012, 6.899] (assumes normal distribution)


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
# Warmup Iteration   1: 13.311 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 5.653 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.655 ±(99.9%) 0.009 ms/op
Iteration   1: 4.660 ±(99.9%) 0.008 ms/op
Iteration   2: 4.485 ±(99.9%) 0.016 ms/op
Iteration   3: 4.482 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.542 ±(99.9%) 1.862 ms/op [Average]
  (min, avg, max) = (4.482, 4.542, 4.660), stdev = 0.102
  CI (99.9%): [2.680, 6.404] (assumes normal distribution)


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
# Warmup Iteration   1: 13.026 ±(99.9%) 0.159 ms/op
# Warmup Iteration   2: 4.676 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.439 ±(99.9%) 0.019 ms/op
Iteration   1: 4.009 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.931 ms/op
                 createUser·p0.999:  20.349 ms/op
                 createUser·p0.9999: 26.152 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   2: 3.938 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.710 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   6.881 ms/op
                 createUser·p0.999:  26.211 ms/op
                 createUser·p0.9999: 29.022 ms/op
                 createUser·p1.00:   30.245 ms/op

Iteration   3: 3.838 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.745 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.555 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  22.734 ms/op
                 createUser·p0.9999: 33.926 ms/op
                 createUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244229
  mean =      3.927 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 443 
    [ 2.500,  5.000) = 235230 
    [ 5.000,  7.500) = 7209 
    [ 7.500, 10.000) = 814 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 71 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.710 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     23.774 ms/op
     p(99.9900) =     30.573 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 12.419 ±(99.9%) 0.167 ms/op
# Warmup Iteration   2: 4.643 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.012 ms/op
Iteration   1: 3.749 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.616 ms/op
                 existUser·p0.50:   3.686 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.398 ms/op
                 existUser·p0.999:  22.456 ms/op
                 existUser·p0.9999: 28.436 ms/op
                 existUser·p1.00:   28.770 ms/op

Iteration   2: 3.565 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.995 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  10.096 ms/op
                 existUser·p0.9999: 25.528 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.712 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.032 ms/op
                 existUser·p0.50:   3.629 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  23.247 ms/op
                 existUser·p0.9999: 32.235 ms/op
                 existUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 261402
  mean =      3.674 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1727 
    [ 2.500,  5.000) = 253964 
    [ 5.000,  7.500) = 4693 
    [ 7.500, 10.000) = 625 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 68 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.283 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     30.109 ms/op
     p(99.9990) =     33.023 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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
# Warmup Iteration   1: 13.171 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.512 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.013 ms/op
Iteration   1: 3.917 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.610 ms/op
                 getUser·p0.50:   3.817 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  22.600 ms/op
                 getUser·p0.9999: 24.369 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   2: 3.821 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.827 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   6.783 ms/op
                 getUser·p0.999:  13.521 ms/op
                 getUser·p0.9999: 27.460 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   3: 3.913 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.516 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  27.502 ms/op
                 getUser·p0.9999: 31.026 ms/op
                 getUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 247100
  mean =      3.883 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 246 
    [ 2.500,  5.000) = 236857 
    [ 5.000,  7.500) = 7944 
    [ 7.500, 10.000) = 1280 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.516 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     22.446 ms/op
     p(99.9900) =     30.189 ms/op
     p(99.9990) =     31.983 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 13.048 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 6.418 ±(99.9%) 0.045 ms/op
# Warmup Iteration   3: 4.549 ±(99.9%) 0.014 ms/op
Iteration   1: 4.525 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.439 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  22.491 ms/op
                 listUser·p0.9999: 27.525 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 4.629 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.584 ms/op
                 listUser·p0.99:   8.323 ms/op
                 listUser·p0.999:  17.397 ms/op
                 listUser·p0.9999: 22.020 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   3: 4.687 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.480 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  18.439 ms/op
                 listUser·p0.9999: 22.496 ms/op
                 listUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208028
  mean =      4.613 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 180007 
    [ 5.000,  7.500) = 23942 
    [ 7.500, 10.000) = 3207 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.439 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      8.339 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     25.257 ms/op
     p(99.9990) =     28.205 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.005 ± 6.891  ops/ms
ClientPb.existUser                       thrpt       3   8.560 ± 2.164  ops/ms
ClientPb.getUser                         thrpt       3   8.401 ± 2.816  ops/ms
ClientPb.listUser                        thrpt       3   6.898 ± 1.312  ops/ms
ClientPb.createUser                       avgt       3   3.819 ± 1.785   ms/op
ClientPb.existUser                        avgt       3   3.728 ± 0.783   ms/op
ClientPb.getUser                          avgt       3   3.955 ± 2.944   ms/op
ClientPb.listUser                         avgt       3   4.542 ± 1.862   ms/op
ClientPb.createUser                     sample  244229   3.927 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.710           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.440           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.776           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.685           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.774           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.573           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.669           ms/op
ClientPb.existUser                      sample  261402   3.674 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.032           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.407           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.283           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.809           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.109           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.063           ms/op
ClientPb.getUser                        sample  247100   3.883 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.516           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.801           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.012           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.446           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.189           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.244           ms/op
ClientPb.listUser                       sample  208028   4.613 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.439           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.169           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.339           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.923           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.257           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.312           ms/op
