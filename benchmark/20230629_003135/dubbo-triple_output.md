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
# Warmup Iteration   1: 1.535 ops/ms
# Warmup Iteration   2: 3.421 ops/ms
# Warmup Iteration   3: 7.170 ops/ms
Iteration   1: 7.421 ops/ms
Iteration   2: 7.755 ops/ms
Iteration   3: 7.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.684 ±(99.9%) 4.301 ops/ms [Average]
  (min, avg, max) = (7.421, 7.684, 7.877), stdev = 0.236
  CI (99.9%): [3.383, 11.986] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.370 ops/ms
# Warmup Iteration   2: 6.437 ops/ms
# Warmup Iteration   3: 7.987 ops/ms
Iteration   1: 8.028 ops/ms
Iteration   2: 7.981 ops/ms
Iteration   3: 8.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.062 ±(99.9%) 1.862 ops/ms [Average]
  (min, avg, max) = (7.981, 8.062, 8.176), stdev = 0.102
  CI (99.9%): [6.199, 9.924] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.183 ops/ms
# Warmup Iteration   2: 5.991 ops/ms
# Warmup Iteration   3: 7.707 ops/ms
Iteration   1: 7.861 ops/ms
Iteration   2: 7.995 ops/ms
Iteration   3: 8.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.962 ±(99.9%) 1.624 ops/ms [Average]
  (min, avg, max) = (7.861, 7.962, 8.029), stdev = 0.089
  CI (99.9%): [6.337, 9.586] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.502 ops/ms
# Warmup Iteration   2: 5.048 ops/ms
# Warmup Iteration   3: 6.880 ops/ms
Iteration   1: 6.561 ops/ms
Iteration   2: 6.936 ops/ms
Iteration   3: 7.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.959 ±(99.9%) 7.483 ops/ms [Average]
  (min, avg, max) = (6.561, 6.959, 7.381), stdev = 0.410
  CI (99.9%): [≈ 0, 14.442] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.835 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.388 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.006 ms/op
Iteration   1: 3.772 ±(99.9%) 0.009 ms/op
Iteration   2: 3.867 ±(99.9%) 0.010 ms/op
Iteration   3: 4.035 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.891 ±(99.9%) 2.430 ms/op [Average]
  (min, avg, max) = (3.772, 3.891, 4.035), stdev = 0.133
  CI (99.9%): [1.462, 6.321] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.072 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.005 ms/op
Iteration   1: 3.885 ±(99.9%) 0.008 ms/op
Iteration   2: 3.887 ±(99.9%) 0.011 ms/op
Iteration   3: 3.850 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.874 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (3.850, 3.874, 3.887), stdev = 0.021
  CI (99.9%): [3.498, 4.251] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.867 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.615 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.010 ms/op
Iteration   1: 3.847 ±(99.9%) 0.005 ms/op
Iteration   2: 3.914 ±(99.9%) 0.003 ms/op
Iteration   3: 3.697 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.819 ±(99.9%) 2.030 ms/op [Average]
  (min, avg, max) = (3.697, 3.819, 3.914), stdev = 0.111
  CI (99.9%): [1.789, 5.850] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.011 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 5.732 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.683 ±(99.9%) 0.009 ms/op
Iteration   1: 4.617 ±(99.9%) 0.008 ms/op
Iteration   2: 4.418 ±(99.9%) 0.020 ms/op
Iteration   3: 4.420 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.485 ±(99.9%) 2.087 ms/op [Average]
  (min, avg, max) = (4.418, 4.485, 4.617), stdev = 0.114
  CI (99.9%): [2.399, 6.572] (assumes normal distribution)


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
# Warmup Iteration   1: 11.871 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.740 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.082 ±(99.9%) 0.016 ms/op
Iteration   1: 3.880 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.352 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  12.386 ms/op
                 createUser·p0.9999: 28.787 ms/op
                 createUser·p1.00:   29.622 ms/op

Iteration   2: 3.908 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.548 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  24.642 ms/op
                 createUser·p0.9999: 28.580 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   3: 3.952 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.210 ms/op
                 createUser·p0.99:   7.102 ms/op
                 createUser·p0.999:  24.027 ms/op
                 createUser·p0.9999: 33.968 ms/op
                 createUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245236
  mean =      3.913 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 921 
    [ 2.500,  5.000) = 232087 
    [ 5.000,  7.500) = 10796 
    [ 7.500, 10.000) = 839 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     23.298 ms/op
     p(99.9900) =     32.403 ms/op
     p(99.9990) =     34.425 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 10.078 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.013 ms/op
Iteration   1: 3.841 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   7.070 ms/op
                 existUser·p0.999:  21.685 ms/op
                 existUser·p0.9999: 24.664 ms/op
                 existUser·p1.00:   26.149 ms/op

Iteration   2: 3.879 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.845 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  13.713 ms/op
                 existUser·p0.9999: 32.662 ms/op
                 existUser·p1.00:   33.882 ms/op

Iteration   3: 3.920 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   5.161 ms/op
                 existUser·p0.99:   6.480 ms/op
                 existUser·p0.999:  29.289 ms/op
                 existUser·p0.9999: 36.110 ms/op
                 existUser·p1.00:   37.749 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247236
  mean =      3.880 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 730 
    [ 2.500,  5.000) = 233148 
    [ 5.000,  7.500) = 11797 
    [ 7.500, 10.000) = 992 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 53 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     21.463 ms/op
     p(99.9900) =     35.211 ms/op
     p(99.9990) =     37.425 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


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
# Warmup Iteration   1: 12.439 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 5.336 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.229 ±(99.9%) 0.014 ms/op
Iteration   1: 3.862 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.827 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   8.851 ms/op
                 getUser·p0.999:  19.595 ms/op
                 getUser·p0.9999: 24.862 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.867 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.626 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  24.321 ms/op
                 getUser·p0.9999: 27.745 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   3: 3.837 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  27.197 ms/op
                 getUser·p0.9999: 32.331 ms/op
                 getUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 248857
  mean =      3.855 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 389 
    [ 2.500,  5.000) = 240028 
    [ 5.000,  7.500) = 6234 
    [ 7.500, 10.000) = 1259 
    [10.000, 12.500) = 480 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 45 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     22.877 ms/op
     p(99.9900) =     31.330 ms/op
     p(99.9990) =     32.622 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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
# Warmup Iteration   1: 14.509 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 5.145 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.767 ±(99.9%) 0.016 ms/op
Iteration   1: 4.632 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  21.690 ms/op
                 listUser·p0.9999: 26.856 ms/op
                 listUser·p1.00:   28.508 ms/op

Iteration   2: 4.441 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.122 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 22.131 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 4.804 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  17.608 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 207694
  mean =      4.621 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 175911 
    [ 5.000,  7.500) = 27315 
    [ 7.500, 10.000) = 3340 
    [10.000, 12.500) = 560 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 150 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      8.913 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     25.370 ms/op
     p(99.9990) =     27.523 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.684 ± 4.301  ops/ms
ClientPb.existUser                       thrpt       3   8.062 ± 1.862  ops/ms
ClientPb.getUser                         thrpt       3   7.962 ± 1.624  ops/ms
ClientPb.listUser                        thrpt       3   6.959 ± 7.483  ops/ms
ClientPb.createUser                       avgt       3   3.891 ± 2.430   ms/op
ClientPb.existUser                        avgt       3   3.874 ± 0.377   ms/op
ClientPb.getUser                          avgt       3   3.819 ± 2.030   ms/op
ClientPb.listUser                         avgt       3   4.485 ± 2.087   ms/op
ClientPb.createUser                     sample  245236   3.913 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.770           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.506           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.742           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.298           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.403           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.914           ms/op
ClientPb.existUser                      sample  247236   3.880 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.096           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.699           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.063           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.849           ms/op
ClientPb.existUser:existUser·p0.999     sample          21.463           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.211           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.749           ms/op
ClientPb.getUser                        sample  248857   3.855 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.087           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.715           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.276           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.653           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.209           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.877           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.330           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.899           ms/op
ClientPb.listUser                       sample  207694   4.621 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.485           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.210           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.913           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.547           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.370           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.508           ms/op
